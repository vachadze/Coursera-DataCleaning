# Coursera-DataCleaning

This repo contains files from Coursera Getting and Cleaning Data course project:
* run_analysis.R file with the script performing the analysis
* CodeBook.md file that describes the variables, the data, and any transformations or work that you performed to clean up the data
* README.md - this file itself

The data represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

* Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
* It should be downloaded and unzipped into R working directory, _*UCI HAR Dataset*_ folder will be created.
* You should run a script from file called _*run_analysis.R*_ that does the following. 
  * Merges the training and the test sets to create one data set.
  * Extracts only the measurements on the mean and standard deviation for each measurement. 
  * Uses descriptive activity names to name the activities in the data set
  * Appropriately labels the data set with descriptive variable names. 
  * From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
* File called _*tidy_dataset.txt*_ will be generated in the working direcotry, containing resulting clean data according to the course project requirements
