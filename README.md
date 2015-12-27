# run_analysis_r
Final project repository for Coursera's "Getting and Cleaning Data" course, December 2015

There exist, raw datasets resulting from data that were collected from accelerometers embedded in the 'Samsung Galaxy S' smartphone. The current objective is to gather the raw data into a single file and analyze the output.

From the original source of the dataset (http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones) we learn that the data have been collected from a group of 30 volunteers within an age bracket of 19-48 years-of-age. These data are organized as follows:  six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) from each volunteer wearing a smartphone (Samsung Galaxy S II) on the waist. Using an embedded accelerometer and gyroscope, 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz were captured. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The Getting and Cleaning Data course assignment requires:
1) that the training and the test datasets be merged to create one data set;
2) extract only the measurements on the mean and standard deviation for each measurement;
3) use descriptive names to appropriate identify the activities in the data set;
4) create a second, independent tidy data set with the average of each variable for each activity and each subject.

Description: The dataset description is available from: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones#

CodeBook: The code book for these data is included within this repository or can be loaded from:
https://github.com/PrairyErth/run_analysis_r/blob/master/CodeBook.txt
