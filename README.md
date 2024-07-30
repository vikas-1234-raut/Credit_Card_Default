Model Evaluation: Confusion Matrix
Overview
In our project, we aim to predict whether credit card holders will default on their payments. We use the Credit Card Default Payment Dataset from the UCI Machine Learning Repository. After training a logistic regression model on the training data, we evaluate its performance using a confusion matrix on the test data.

Confusion Matrix
The confusion matrix is a table used to describe the performance of a classification model. It shows the counts of actual versus predicted classifications. Here’s a breakdown of the terms used in the confusion matrix:

True Positive (TP): Cases in which the model predicted 'yes' (default) and the actual value was also 'yes' (default).
True Negative (TN): Cases in which the model predicted 'no' (non-default) and the actual value was also 'no' (non-default).
False Positive (FP): Cases in which the model predicted 'yes' (default) but the actual value was 'no' (non-default).
False Negative (FN): Cases in which the model predicted 'no' (non-default) but the actual value was 'yes' (default).
Accuracy Calculation
The accuracy of the model is calculated using the formula:

Accuracy=  TP+TN / Total Samples
​


 

Where:

TP is True Positive
TN is True Negative
Total Samples is the sum of all instances in the dataset.
