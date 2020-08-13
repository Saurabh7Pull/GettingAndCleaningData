## **Codebook for Getting and Cleaning Data (Course 3 in the Data Science Specialization by JHU on Coursera)**
### Saurabh Somkuwar's Course Project

**Getting and Cleaning Data Course Project**

The purpose of this project is to demonstrate our ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

**Data set** - Human Activity Recognition Using Smartphones Data Set

**Description** - 
Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

For more information visit: [UCI Machine Learning Repository: Human Activity Recognition Using Smartphones Data Set](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

**Attribute Information**
For each record in the dataset it is provided:
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
- Triaxial Angular velocity from the gyroscope.
- A 561-feature vector with time and frequency domain variables.
- Its activity label.
- An identifier of the subject who carried out the experiment.

**Tasks** - 
With the dataset available at our disposal, we were required to carry out the following tasks:
1. Merge the training and the test sets to create one data set.
2. Extract only the measurements on the mean and standard deviation for each measurement.
3. Use descriptive activity names to name the activities in the data set
4. Appropriately label the data set with descriptive variable names.
5. From the data set in step 4, create a second, independent tidy data set with the average of each variable for each activity and each subject.

**R Script** - 
These tasks were performed and recorded in a single R script - [run_analysis.R](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/run_analysis.R)
The contents of the above file are organized as follows:
1. The necessary packages were loaded and the data was obtained.
2. The activity labels and features were loaded.
3. The training datasets were loaded.
4. The testing datasets were loaded.
5. The datasets were merged together.
6. The classLabels were converted to activityName

**Merged Dataset** - 
The resulting dataset was exported in .txt format as [tidyData.txt](https://github.com/Saurabh7Pull/GettingAndCleaningData/blob/master/tidyData.txt)
