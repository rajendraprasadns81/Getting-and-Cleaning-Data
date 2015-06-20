
The features selected for this data frame came from the transformation of the data in the "Human Activity Recognition Using Smartphones Dataset Version 1.0", which in turn have been taken from experiments carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz data were captured, of accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ

Download the data from below link

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Unzip file.


See the README.txt file for the detailed information on the dataset. Also see features_info.txt for the details of variables and features.txt for the list of variables.


The files that will be used to load data are listed as follows:
•	test/subject_test.txt
•	test/X_test.txt
•	test/y_test.txt
•	train/subject_train.txt
•	train/X_train.txt
•	train/y_train.txt



1.	Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
2.	values of Varible Subject consist of data from “subject_train.txt” and subject_test.txt"
3.	Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
4.	Names of Varibles Features come from “features.txt”
5.	levels of Varible Activity come from “activity_labels.txt”



So we will use Activity, Subject and Features as part of descriptive variable names for data in data frame.

2.Read data from the files into the variables

Read the Activity files

Read the Subject files

Read Features files

Appropriately labels the data set with descriptive variable names

In the former part, variables activity and subject and names of the activities have been labelled using descriptive names.In this part, Names of Feteatures will labelled using descriptive variable names.

•	prefix t is replaced by time
•	Acc is replaced by Accelerometer
•	Gyro is replaced by Gyroscope
•	prefix f is replaced by frequency
•	Mag is replaced by Magnitude
•	BodyBody is replaced by Body


Merge the training and the test sets to create one data set.

Extract only the measurements on the mean and standard deviation for each measurement by subsetting Name of Features by measurements on the mean and standard deviation.

Create a second, independent tidy data set  with the average of each variable for each activity and each subject based on the data set in previous step.






