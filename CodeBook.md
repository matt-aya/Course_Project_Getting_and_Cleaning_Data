
Human Activity Recognition Using Smartphones Dataset Code_Book :
Version 1.0


First ......The Original zip file:

Data-sets located in two sets Training and Test

The data-sets capture measurements of six activities performed by 30 volunteers

Number of Instances: 10299

Number of Attributes: 561


Second ......The way the script works :

1. set working directory using setwd

2. Merges the training and the test sets to create one data set

3. Extracts only the measurements on the mean and standard deviation for each measurement.

4. Uses descriptive activity names to name the activities in the data set

5. Appropriately labels the data set with descriptive variable names.

6. From the data set in step 5, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

7. Finally write the tidy data set created in step 5 as a txt file created with write.table() using row.name=FALSE .

8. the final result : "tidy_dataset_with_averages.txt"


Third ......Which includes : 

180 rows ID by 30 volunteers performing 6 activities 30 * 6 = 180

68 columns described as the following :

subject :
           
           From 1 to 30
           
           a group of 30 volunteers
           
activity :
           
           walking
           
           walkingupstairs
           
           walkingdownstairs
           
           sitting
           
           standing
           
           laying
           
All the following 66 columns names are the averages of the variables :
           
tbodyacc-mean-x
tbodyacc-mean-y
tbodyacc-mean-z
tbodyacc-std-x
tbodyacc-std-y
tbodyacc-std-z
tgravityacc-mean-x
tgravityacc-mean-y
tgravityacc-mean-z 
tgravityacc-std-x 
tgravityacc-std-y 
tgravityacc-std-z
tbodyaccjerk-mean-x 
tbodyaccjerk-mean-y 
tbodyaccjerk-mean-z 
tbodyaccjerk-std-x
tbodyaccjerk-std-y 
tbodyaccjerk-std-z 
tbodygyro-mean-x 
tbodygyro-mean-y
tbodygyro-mean-z 
tbodygyro-std-x 
tbodygyro-std-y 
tbodygyro-std-z
tbodygyrojerk-mean-x 
tbodygyrojerk-mean-y 
tbodygyrojerk-mean-z 
tbodygyrojerk-std-x
tbodygyrojerk-std-y 
tbodygyrojerk-std-z 
tbodyaccmag-mean 
tbodyaccmag-std
tgravityaccmag-mean 
tgravityaccmag-std 
tbodyaccjerkmag-mean 
tbodyaccjerkmag-std
tbodygyromag-mean 
tbodygyromag-std 
tbodygyrojerkmag-mean 
tbodygyrojerkmag-std
fbodyacc-mean-x 
fbodyacc-mean-y 
fbodyacc-mean-z 
fbodyacc-std-x 
fbodyacc-std-y
fbodyacc-std-z 
fbodyaccjerk-mean-x 
fbodyaccjerk-mean-y 
fbodyaccjerk-mean-z
fbodyaccjerk-std-x 
fbodyaccjerk-std-y 
fbodyaccjerk-std-z 
fbodygyro-mean-x
fbodygyro-mean-y 
fbodygyro-mean-z 
fbodygyro-std-x 
fbodygyro-std-y 
fbodygyro-std-z
fbodyaccmag-mean 
fbodyaccmag-std 
fbodybodyaccjerkmag-mean 
fbodybodyaccjerkmag-std
fbodybodygyromag-mean 
fbodybodygyromag-std 
fbodybodygyrojerkmag-mean
fbodybodygyrojerkmag-std


A full description of the original data_set is available at the site where the data was obtained: 

"http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones "


