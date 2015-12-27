Getting And Cleaning Data
=========================
Course Project completed on 26th Dec 2015
--------------
1. Download the data from the source: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
2. Unzip the data in the working directory.
3. Put the file, `run_analysis.R` in the working directory.
4. Run the file, by using source command, `source("run_analysis.R")`
5. The code will do the following,
    * Load both training dataset and testing dataset
    * Merges both training and test sets
    * Extracts only measurement on mean and standard deviation.
    * Uses Descriptive activity names to name the activities in the dataset.
    * Appropriately labels the data set with descriptive variable names.
    * Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
6. The created tidy dataset will be there in the working directory, named `tidy.txt`
7. Required Packages
    * reshape2
    * data.table
    
