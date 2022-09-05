# Credit Risk Analysis

Overview of the Analysis

We have sample datasets containing loans, along with some relevant information. Included in the dataset are loans that have a high risk of defaulting. Because we already have the data for healthy and high risk loans, it is a good candidate for supervised learning. With supervised learning, we can make predictions about new data and likely predict which loans in the future will be good or high risk.

The data provided by a peer-to-peer lending services company will help build a model to identify the creditworthiness of borrowers. To help us with our prediction, we are going to do these steps:

* Check for any class imbalance.

* Apply sampling techniques and use machine learning models to make accurate predictions for imbalanced data.

* Compare the classification models and sampling algorithms.

How we do it:

* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Predict a Logistic Regression Model with Resampled Training Data

Results

Logistic Regression Model with the Original Data:

* Model accuracy is 95%, Precision avg 99%, and Recall scores avg 99%.

Logistic Regression Model with Resampled Training Data:

* Model accuracy is 95%, Precision avg 99%, and Recall scores avg 99%.

Summary

Based on the Logistic Regression Models (first fit with original data and another fit with oversampled data), both healthly (0) and high risk (1) loans were also labeled with a 95% Geometric Mean, indicative of good performance in the classification. The precision is 100% for the healthy loans while 85% (a bit low) for the high risk loans. Based on Recall, we caught 99% for healthy loan and 91% for high risk loans. The F1 score for healthy loans is 100%. But high risk loans have an 88% F1 score, which is relatively low. Overall, the average Model accuracy is 95%, average Precision is 99%, and average recall is 99% as well. 