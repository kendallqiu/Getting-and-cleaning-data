# Getting-and-cleaning-data
For course project
# 1. Merge the training and the test sets to create one data set.

## step 1: download zip file and unzip data
## step 2: load data
## step 3: merge traindata and testdata

# 2. Extract only the measurements on the mean and standard deviation for each measurement. 

# 3. Uses descriptive activity names to name the activities in the data set

# 4. Appropriately labels the data set with descriptive variable names.

# 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# Write it as MeanData.txt
write.table(groupData, "D:/Users/Documents/MeanData.txt", row.names = FALSE)
