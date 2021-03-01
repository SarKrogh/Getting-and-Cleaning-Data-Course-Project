# This is the code book for the project

# About the source data

The source data are from the Human Activity Recognition Using Smartphones Data Set. A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# About R script

File with R code "run_analysis.R" performs the 5 following steps:

1. Reading in the files and merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement
3. Using descriptive activity names to name the activities in the data set
4. Labeling the data set with descriptive variable names
5. Creating a second, independent tidy data called "finaltinydata.txt" set with the average of each variable for each activity and each subject
  
# About variables:

x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
x_data, y_data and subject_data merge the previous datasets to further analysis.

