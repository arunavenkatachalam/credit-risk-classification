# credit-risk-classification

# Credit Risk Analysis Report

## Overview of Analysis
This dataset consist of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. We use various techniques to train and evaluate a model based on loan risk. 

## Results of Machine Learning Model with the original and resampled data

1. Fit a logistic regression model by using the training data
2. Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model
3. Evaluate the model’s performance by identifying the balanced_accuracy score, generate a confusion matrix and print the classification report for the model.
4. The balance accuracy score for logistic regression model is 96%. The logistic regression model predict the healthy loan with 100% precision and high risk loan with 85% precision.
5. Fit a logistic regression model with resampled training data using RandomOverSampler.
6. Save the predictions for the logistic regression model with resampled training data by using the testing feature data (X_resample) and the fitted model
7. Evaluate the logistic regression model with resampled training data by identifying the balanced_accuracy score, generate a confusion matrix and print the classification report for the model.
8. The balance accuracy score for logistic regression model with resampled training data is 99% and the high risk loan the recall value has increased to 99%

## Summary

The Random oversampled model with the logistic regression has performed well with 99% balance accuracy score, the healthy loan has a 100% precision and 99% recall value whereas the high risk loan has 84% precision and 99% recall value. I recommend Randam oversampled model compared to the original logistic regression model based on the results obtained from the models. 
