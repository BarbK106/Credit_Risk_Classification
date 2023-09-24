# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to evaluate a model based on loan risk (healthy loans versus high-risk loans). A dataset of historical lending activity from a peer-to-peer lending services company was used to build a model that can identify the creditworthiness of borrowers.

Logistic Regression was used and the historical data and model evaluated using a confusion matrix and classfication report. The same analysis was then repeated on resampled data using RandomOverSampler.

## Results

Machine Learning: Logistic Regression Model Using Original Data
Accuracy: 0.9520479254722232
Precision: 1.0 (healthy loans)/ 0.85 (high-risk loans)
Recall Scores: 0.99 (healthy loans)/0.91 (high-risk loans)

Machine Learning: Logistic Regression Model Using Resampled Data
Accuracy: 0.9936781215845847
Precision: 1.0 (healthy loans)/ 0.84 (high-risk loans)
Recall Scores: 0.99 (healthy loans)/ 0.99 high-risk loans)


## Summary

Both logistic regression models were very accurate in predicting healthy loans (1.0) and less accurate in predicting risky loans (0.85 and 0.84)
The logistic regression model using the resampled data had a higher accuracy score (0.99 versus 0.95) and was better at predicting both healthy and high-risk loans versus the model using the original data, based on the recall scores 0.99, however the precision for high-risk loans was not improved.
In summary, the model using the resampled data showed increased accuracy in detecting high risk loans based on the classification report and the balanced accuracy score.  Exploring additional classification models to increase the predicted accuracy for high-risk loans is recommended since the above models had a large margin of error for predicting high risk loans.

