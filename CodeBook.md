File with R code "run_analysis.R" performs the 5 following steps (in accordance assigned task of course work):

#Steps in producing the code and the result in the tidy data set text file
#Reading in the files and merging the training and the test sets to create one data set.
#1.1 Reading files
#1.1.1 Reading trainings tables
#1.1.2 Reading testing tables
#1.1.3 Reading feature vector
#1.1.4 Reading activity labels
#1.2 Assigning variable names
#1.3 Merging all data in one set
#Extracting only the measurements on the mean and standard deviation for each measurement
#2.1 Reading variable names
#2.2 Create vector for defining ID, mean and standard deviation
#2.3 Making nessesary subset from merged data set
#Using descriptive activity names to name the activities in the data set
#Appropriately labeling the data set with descriptive variable names
#Creating a second, independent tidy data set with the average of each variable for each activity and each subject
#5.1 Making second tidy data set
#5.2 Writing second tidy data set in txt file

#xtrain, ytrain, xtest, ytest, subtrain and subtest contain the data from the downloaded files.
#combineX, combineY and combineSubj merge the previous datasets to further analysis
#df essentially merges the combineX and Y into a single dataframe and colnames just takes the column names of said dataframe.
#df2 is essentially more refined dataframe which has been selected based on the regex pattern called from df