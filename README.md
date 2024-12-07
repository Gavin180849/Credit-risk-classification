# Credit-risk-classification
## Overview of the Analysis
The purpose of the analysis is to create supervised machine learning that will predict if a loan is healthy or high risk. The financial information was based off of a number of factors, loan size, interest rate, borrower income, debt to income ration, number of account, derogatory marks, and total debt. Using the financial information, predictions could be made if the loan will be healthy (0) or high risk (1). The stages of machine learning used were splitting and labeling the data into healthy and high risk. It was then split into testing data sets. A logistical regression model was used to make predictions for loan status, healthy (0), or high risk (1). The models performance was evaluated based on accuracy, precision and recall scores.

## Results
* Description of Model 1 Accuracy, Precision, and Recall scores.
   * The Accuracy score was 99.3%.
   * Precision for healthy loans was 100%
   * Precision for high risk loans was 87%
   * Recall for healthy loans was 100%
   * Recall high risk loans was 95%

## Summary
The logistic regression model does a good job of predicting if someone is going to go into default on their loan with an accuracy score of 99.3%. The precision and recall for the healthy loans (0) was 100%. the precision for high risk loans was 87% with a recall of 95%, which is still fairly good. 

The data for high risk loans was imbalanced, only accounting for 625 of the total 19,384 data sets. Due to limited number of high risk loans for the model to learn, improvements could be made with more high risk data sets. Healthy loans accounted for 18,759 of the 19,384 data sets. Due to the large number of data sets the information for machine learning is highly accurate. 

