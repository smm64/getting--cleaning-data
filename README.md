# Getting and Cleaning Data - Course Project

Course project for the Getting and Cleaning Data Coursera course.
Requires the plyr library to be installed in R.
The script `run_analysis.R` does the following:

1. Loads and merges the training and test sets to create one data set 
2. Extracts the measurements on the mean and standard deviation for each measurement
3. Names the activities in the data set
4. Labels the data set with descriptives
6. Creates a tidy dataset that consists of the average value of each
   variable for each subject and activity pair.

Produces the output 'averageddata.txt'.