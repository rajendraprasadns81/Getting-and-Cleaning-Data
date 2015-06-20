# Getting-and-cleaning-data-assignment

Install "reshape2" package, call library(reshape2)

run_analysis.R R-script on  Human Activity Recognition Using Smartphones Dataset.

First, read all required .txt files and label the datasets 

Read all activities and their names and label the aproppriate columns 

Read the dataframe's column names  and assign it to  "features" variable.

 
Names of Features  labelled using descriptive variable names

Read the test data and label the dataframe's columns 

Read the training data and label the dataframe's columns

Read the ids of the test subjects,activity id's of test data set  and label the the dataframe's columns

 

Read the ids of the test subjects,activity id's of training dataset and label


column bind  the test subject id's, the test activity id's  and the test data into one dataframe 

column bind the test subject id's, the test activity id's  and the test data into one dataframe 

Combine the test data and the train data into one dataframe 


Keep only columns refering to mean() or std() values 

Merge the activities datase with the mean/std values datase to get one dataset with descriptive activity names 

Melt the dataset with the descriptive activity names for better handling 

Cast the melted dataset according to  the average of each variable for each activity and each subject

Create a file with the new tidy dataset 