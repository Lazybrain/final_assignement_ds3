# The run_analysis.R script performs the data preparation following the 5 steps describeb in the project 

we first starting by downloading the project dataset named UCI HAR Dataset and then extract the files 

second we assign each data to variables example : 

x_test <- test/X_test.txt : 2947 rows, 561 columns


Then we merge the training and the test sets to create one data set by using the rbind and cbind function 


after we extract only the measurements on the mean and standard deviation for each measurement using Tidydata()


Uses descriptive activity names to name the activities in the data set
Entire numbers in code column of the TidyData replaced with corresponding activity taken from second column of the activities variable

Appropriately labels the data set with descriptive variable names
code column in TidyData renamed into activities,grouping and finally outputing a txt file of the final data 


