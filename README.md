# CreditCard_fraud_detection
This repository deals with credit card fraud detection. The data is taken from kaggle, it has 29 features and 1 class label.
Steps to reproduce-
1) setup your kaggle api
2) run the starting lines of code
3) You will see a kaggle folder created
4) drag and drop you kaggle.json file into it and then proceed with other lines
## I have applied 3 Algorithms -logistic regression, gradient boosting and Random forest
** Befor applying these, since the class lables were imbalanced so I have used undersampling technique to drop some rows of majority class.
Step by step process-
1) import data using kaggle api
2) plot the count of class label, and divide data into train and test
3) balance the class label of training data by using undersampling technique (because datasize is 200k+ so if we oversample, it might overfit)
4) plot correlation matrix and chech the relaion of target with each feature, in our data time had almost 0 relation, so we removed it.
5) Apply ML models
6) compare their accuracies
