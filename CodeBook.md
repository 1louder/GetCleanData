Samsung Data Set
========================================================
This codebook explains the script, run_analysis.R.  The data comes from SmartLab and was collected from 30 individuals.  Each person's activity was tracked via their Samsung Galaxy S II smart phone.  

There were over 500 total variables in the study, though only 79 were used for the run_analysis.R report.  The data went into training and test datasets.  After merging the numbers, a column was added to clearly label the type of activity that occurred in each entry.  These activities included walking, walking upstairs, walking downstairs, sitting, standing, and laying.  Body accelerations were computed and the average mean and average standard deviation calculations were made.  

Finally, a tidy data set was produced and written to the user's machine.  

Here is a list of variables found in the tidy data set:

[1] "tbodyaccmeanx" "tbodyaccmeany" "tbodyaccmeanz" "tgravityaccmeanx" "tgravityaccmeany" "tgravityaccmeanz"
[7] "tbodyaccjerkmeanx" "tbodyaccjerkmeany" "tbodyaccjerkmeanz" "tbodygyromeanx" "tbodygyromeany" "tbodygyromeanz"
[13] "tbodygyrojerkmeanx" "tbodygyrojerkmeany" "tbodygyrojerkmeanz" "tbodyaccmagmean" "tgravityaccmagmean" "tbodyaccjerkmagmean"
[19] "tbodygyromagmean" "tbodygyrojerkmagmean" "fbodyaccmeanx" "fbodyaccmeany" "fbodyaccmeanz" "fbodyaccmeanfreqx"
[25] "fbodyaccmeanfreqy" "fbodyaccmeanfreqz" "fbodyaccjerkmeanx" "fbodyaccjerkmeany" "fbodyaccjerkmeanz" "fbodyaccjerkmeanfreqx"
[31] "fbodyaccjerkmeanfreqy" "fbodyaccjerkmeanfreqz" "fbodygyromeanx" "fbodygyromeany" "fbodygyromeanz" "fbodygyromeanfreqx"
[37] "fbodygyromeanfreqy" "fbodygyromeanfreqz" "fbodyaccmagmean" "fbodyaccmagmeanfreq" "fbodybodyaccjerkmagmean" "fbodybodyaccjerkmagmeanfreq" [43] "fbodybodygyromagmean" "fbodybodygyromagmeanfreq" "fbodybodygyrojerkmagmean" "fbodybodygyrojerkmagmeanfreq" "tbodyaccstdx" "tbodyaccstdy"
[49] "tbodyaccstdz" "tgravityaccstdx" "tgravityaccstdy" "tgravityaccstdz" "tbodyaccjerkstdx" "tbodyaccjerkstdy"
[55] "tbodyaccjerkstdz" "tbodygyrostdx" "tbodygyrostdy" "tbodygyrostdz" "tbodygyrojerkstdx" "tbodygyrojerkstdy"
[61] "tbodygyrojerkstdz" "tbodyaccmagstd" "tgravityaccmagstd" "tbodyaccjerkmagstd" "tbodygyromagstd" "tbodygyrojerkmagstd"
[67] "fbodyaccstdx" "fbodyaccstdy" "fbodyaccstdz" "fbodyaccjerkstdx" "fbodyaccjerkstdy" "fbodyaccjerkstdz"
[73] "fbodygyrostdx" "fbodygyrostdy" "fbodygyrostdz" "fbodyaccmagstd" "fbodybodyaccjerkmagstd" "fbodybodygyromagstd"
[79] "fbodybodygyrojerkmagstd" "activity" "trainortest" "subjectid"