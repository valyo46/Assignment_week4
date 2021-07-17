##"The supporting metadata in this data are the name of the features and the name of the activities. They are loaded into variables featureNames and activityLabels.Both training and test data sets are split up into subject, activity and features. They are present in three different files.We use combine the respective data in training and test data sets corresponding to subject, activity and features. The results are stored in subject, activity and features.The columns in the features data set are named from the metadata in featureNames.The data in features,activity and subject are merged and the complete data is now stored in completeData.Extract the column indices that have either mean or std in them.Add activity and subject columns to the list and look at the dimension of completeData.We create extractedData with the selected columns in requiredColumns. And again, we look at the dimension of requiredColumns.By examining extractedData, we can say that the following acronyms can be replaced:

#Acc can be replaced with Accelerometer

#Gyro can be replaced with Gyroscope

#BodyBody can be replaced with Body

#Mag can be replaced with Magnitude

#Character f can be replaced with Frequency

#Character t can be replaced with Time.
#We create tidyData as a data set with average for each activity and subject. Then, we order the enties in tidyData and write it into data file Tidy.txt that contains the processed data."