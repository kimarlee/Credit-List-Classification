# Credit-List-Classification
Module 20 Challenge

## Overview of the Analysis

The purpose of this analysis was develop a machine learning model to help predict the risk level of loans. We were to determine if a loan is healthy (0) or high-risk (1) using financial lending data that was obtained in the csv file.

A logistic regression model was chosen to evaluate how effectively it can predict loan risk based on the features.

## Results

The performance of the logistic regression model was evaluated using the confusion matrix and the classification report.
•    Accuracy Score: 0.99 
•    Precision Score: 
  o    Healthy Loans (0): 1.00
  o    High-Risk Loans (1): 0.84
•    Recall Score: 
  o    Healthy Loans (0): 0.99 
  o    High-Risk Loans (1): 0.94
•    F-1 Score: 0.89 
•    Confusion Matrix: 
  [[18655 110] 
  [ 36 583]]


## Summary

The logistic regression model demonstrated outstanding results, especially in identifying healthy loans with 100% precision and 99% recall. It also does exceptionally well with identifying high-risk loans with 84% precision and 94% recall.

This model would be highly recommended for identifying both healthy and high risk loans due to the above scores. The low false negative rate is also good to note since it reduces the risk of mistakenly approving high-risk loans.

