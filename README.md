# FraudDetection

Problem is to determine whether a transcation from one bank account to another one is fraudelt or not. The dataset can be found here https://www.kaggle.com/code/sonawanelalitsunil/fraud-detection-dataset-ml-99-99, and contains over 6.3M rows.

Since the dataset is so large, normal ML methods are very hard to train. So we opt for Logistic Regression and Light-Gradient Boosting. The best accuracy is reached with LGBM. Using a Bayesian optimizer, we reach an accuracy of 99.999% on the hold-out test set.
