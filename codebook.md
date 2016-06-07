
Script run_analysis. entails the 5 steps for course project's definition.

1. data is merged using the rbind() function. 
2. Measures dataset are extracted from  mean and standard deviation  
3. Data cleansing of extracted name by correct names from the features.txt
4. Updated activity data with values 1:6.
5. Activity names & IDs are substitued in data
6. column names are update with meaninful names
7. Averages_data.txt file is generated and uploaded.  Generated new dataset.

Variables
containa the data from the downloaded files
x_train
y_train
x_test
y_test
subject_train
subject_test 

Merge above dataset
x_data
y_data
subject_data

Contains the correct name: x_data dataset
Column names stored mean_and_std_features

Merge o all_data merges x_data, y_data and subject_data in dataset.

Averages_data shows relevant averages and is stored .txt file. 