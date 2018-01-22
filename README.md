# CleaningData

Script Follows the direction step by step
1. Merge the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Variables
- trainingData: reads in train related raw data
- testData: reads in test related raw data
- finalData: merged data. later refined for tidy dataset purpose
- tidyData: the final output data
