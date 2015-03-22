---
title: "Human Activity Recognition Using Smartphones Data Set"
author: "Lim Poh Guan"
date: "Sunday, March 15, 2015"
output: html_document
---
Getting and Cleaning Data: ourse Project

Readme.md (how all of the scripts work and how they are connected)

#Introduction
This repository contains my work for the course project for the Coursera course "Getting and Cleaning data", part of the Data Science specialization.


#About the raw data
The features are unlabeled and can be found in the x_test.txt. The activity labels are in the y_test.txt file. The test subjects are in the subject_test.txt file.

The following files are:

- 'features.txt': List of all features.

- 'activity_labels.txt': Links the class labels with their activity name.

- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 


#About the script (run_analysis.R)
1. Install package and load library data.table
2. Read in the all data using read.table() function for the Test and Train file
3. Merge the data set of train and test using function rbind() and cbind()
4. Extracts only the mean and standard deviation for each measurement with grep() function
5. Label the activities in the data set descriptive activity names using as.character()
6. Display the current variables names with the function names() and replace the current variables names with the function gsub()


#About the Output
Created an output file named ""Tiny.txt" when the program run_analysis.R is run.  The function used is write.table().  The output is an independent tidy data set with the average of each variable for each activity and each subject.


#About the Code Book
The CodeBook.md file describes the variables, the data, and any transformations or work that performed to clean up the data
