Code Book:

subject_test : subject IDs for test

subject_train : subject IDs for train

X_test : values of variables in test

X_train : values of variables in train

y_test : activity ID in test

y_train : activity ID in train

activity_labels : Description of activity IDs in y_test and y_train

features : Description of each variables in X_test and X_train

dataSet : bind of X_train and X_test

MeanStdOnly : a vector of only mean and std labels extracted from 2nd column of features

dataSet : dataSet will only contain mean and std variables

CleanFeatureNames : a vector of "clean" feature names

subject : bind of subject_train and subject_test

activity : bind of y_train and y_test

act_group : factored activity column of dataSet

baseData : melted tall and skinny dataSet

secondDataSet : casete baseData which has means of each variables