## The data
The data is collected from the following link:
<https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip>

And the code book for said data set is found here:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


## The R script

run_analysis.r: This file contains the code implemented to do the steps on the assignment for the course
  > this steps were: 
> 
>   1. Merges the training and the test sets to create one data set.
>   2. Extracts only the measurements on the mean and standard deviation for each measurement.
>   3. Uses descriptive activity names to name the activities in the data set
>   4. Appropriately labels the data set with descriptive variable names.
>   5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The script does all of those things and the output data can be found in the file Finaldata.txt


