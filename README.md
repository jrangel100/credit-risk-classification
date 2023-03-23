# credit-risk-classification

## Overview

The purpose of this analysis is to build and evaluate several machine learning models to assess credit risk. The dataset used in this analysis contains information on borrowers and whether or not they have had difficulty paying back loans in the past. The objective is to build a model that accurately predicts whether a borrower is likely to default on a loan.

## Results:
**Logistic Regression**
* Accuracy Score: 0.99
* Precision Score: 0.85
* Recall Score: 0.91
* F1-Score: 0.88

**Logistic Regression with Resampled data**
* Accuracy Score: 0.99
* Precision Score: 0.84
* Recall Score: 0.99
* F1-Score: 0.91

## Summary

Based on the results, both machine learning models performed well in predicting credit risk. The Logistic Regression model with resampled data had the highest recall score of all models, at 0.99, but had a lower precision score of 0.84. The standard Logistic Regression model had slightly lower recall and precision scores than the resampled version, but still performed well with an accuracy score of 0.99.

Given the high accuracy scores and consistent precision and recall scores across both models, we recommend using either the Logistic Regression or Logistic Regression with resampled data for predicting credit risk. These models provide a high level of accuracy and reliability, and their ability to accurately predict which borrowers are likely to default on loans can help the company make informed decisions when it comes to lending.

However, it's important to note that the models were trained on a relatively small dataset, and their performance on larger datasets may vary. Additionally, the models were trained using a specific set of features, and their performance may vary when applied to different features. Therefore, it's recommended to test the models on new data and perform regular model evaluations to ensure their continued accuracy and reliability.
