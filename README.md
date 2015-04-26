#run_analysis.R

1)One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

2) Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

3) The run_analysis.R script will read the test and train data as data frame,
"test/X_test.txt" "test/y_test.txt" "test/subject_test.txt" "train/X_train.txt", "train/y_train.txt" "train/subject_train.txt".

	•Read the activity labels and the 561 features.
	•Merge the X_test and X_train into mereged_df.
	•Merge the subjects and activity (Y_test/train) columns to the merged_df.
	•Extract the mean and std columns from the merged df.
	•Computes the average of each variable for each activity and each subject.
	•Writes the tidy data to a text and csv file.

