# Credit Card Fraud Detection using isolation forest and Local Outlier Factor(LOF) Algorithm

-Detection of fraudulent transactions. Isolation Forest algorithm gave an ideal classification accuracy than LOF, the reason being the problem statement was clearly an application of class imbalance.
-Dataset had been extracted from kaggle containing transactions made by credit cards in September 2013 by European cardholders. Features in the dataset already underwent PCA transformations so as to preserve the confidentiality of the sensitive data.
-The code prints out the number of false positives it detected and compares it with the actual values. This is used to calculate the accuracy score and precision of the algorithms. The fraction of data we used for faster testing is 10% of the entire dataset. The complete dataset is also used at the end and both the results are printed.
