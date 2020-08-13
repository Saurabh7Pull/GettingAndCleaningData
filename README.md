## GettingAndCleaningData
This repository has been created as required for the Course Project of Getting and Cleaning Data.
[Getting and Cleaning Data](https://www.coursera.org/learn/data-cleaning) is the third course in the Data Science Specialization offered by Johns Hopkins University on Coursera.

**Course Project** - The purpose of this project is to demonstrate one's ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

The repository contains the following: 
1. A merged **tidy data set** [tidyData.txt](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/tidyData.txt)
2. A **Codebook** that describes the variables, the data, and any transformations or work that I performed to clean up the data [Codebook.md](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/Codebook.md)
3. An **R Script** that performs the required analysis [run_analysis.R](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/run_analysis.R)


**R Script** [run_analysis.R](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/run_analysis.R) - This script performs the following functions:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The **resultant tidy data set** obtained from [run_analysis.R](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/run_analysis.R) was exported in the form of a .txt file [tidyData.txt](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/tidyData.txt)

All the actions performed throughout the project with their references have been mentioned in the [Codebook.md](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/Codebook.md). It also contains information about the data source, description of data, attribute information, and the tasks performed.
