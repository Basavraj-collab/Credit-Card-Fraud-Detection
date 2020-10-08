# Credit-Card-Fraud-Detection
Information about data set
The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. 
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues original features are not provided and more background information about the data is also not present. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

Flow of Project
Have done Exploratory Data Analysis on full data, for unbalanced data resampling is done and then the that data is used for various algorithms. For KNN algorithm value of K is determined by CV_Scores.
Evaluation is done by plotting ROC cure and Confusion Matrix for each algorithm.
