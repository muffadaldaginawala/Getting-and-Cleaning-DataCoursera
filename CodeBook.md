Description
========================================
This book descirbes the variables, data and the work performed to clean up the data.

Source and Information
=========================================

Original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Description :http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Data
========================================
he dataset includes the following files:

1.)'README.txt' , 2.)'features_info.txt': Shows information about the variables used on the feature vector , 3.)features.txt': List of all features. 4.)'activity_labels.txt': Links the class labels with their activity name. 5.)'train/X_train.txt': Training set. 6.) 'train/y_train.txt': Training labels. 7.)'test/X_test.txt': Test set. 8.)'test/y_test.txt': Test labels.

Transformation 
==========================================

There are 5 parts:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

How we run it
===========================================

Require reshapre2 and data.table librareis.
Load both test and train data,the features and activity labels.
Extract the mean and standard deviation column names and data.
Process the data. There are two parts processing test and train data respectively.
Merge data set.

