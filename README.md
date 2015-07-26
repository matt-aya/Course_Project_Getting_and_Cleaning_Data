
Course Project :

The files required for the course project are listed in this same repo/directory as following:

1. README.md
2. run_analysis.R
3. tidy_dataset_with_averages.txt
4. CodeBook.md

...Before you start :

The data linked represent data collected from the accelerometers from the Samsung Galaxy S smartphone.

1. Download and unzip the from here...

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

2. You need to copy the run_analysis.R into the same directory created from unzipping the previous link.

directory name is "UCI HAR Dataset"

3. in your Rstudio, set your working directory to where u unziped "UCI HAR Dataset"

now you can start going through the script.

...The way the script works :

1. set working directory using setwd

2. Merges the training and the test sets to create one data set

3. Extracts only the measurements on the mean and standard deviation for each measurement.

4. Uses descriptive activity names to name the activities in the data set

5. Appropriately labels the data set with descriptive variable names.

6. From the data set in step 5, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

7. Finally write the tidy data set created in step 5 as a txt file created with write.table() using row.name=FALSE .

8. the final result : "tidy_dataset_with_averages.txt" which is included in this repo/directory.




