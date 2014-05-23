GetCleanData
============

The data for this project was comprised from a group of files from the following zip file:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.  

Specifically, the following files within that zip file were used: 

X_test.txt
y_test.txt
subject_test.txt
X_train.txt
y_train.txt
subject_train.txt
features.txt

Within the code, the files are renamed for simplicity, as follows:

testX, testY, testSubject, trainX, trainY, and trainSubject

The files above are combined into a single dataset, denoted by the variable, dat.

Mean and standard deviation calculations are used on entries with the words, "std" or "mean" in them.  

A column is added to the full dataset that names the type of activity for each row.  The column is named activityNames and the values include Walking, Walking_Upstairs, Walking_Downstairs, Sitting, Standing, and Laying.  

A final tidy data set, "activityDataset.txt" is produced and written into the working directory of the user.  This dataset includes all the activity names that were derived earlier in the program.  
