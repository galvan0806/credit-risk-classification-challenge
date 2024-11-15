# credit-risk-classification-challenge

## Credit Risk Analysis Report

<p align="center">
  <img src="Credit_Risk/Resources/credit_risk.jpg" alt="Credit Risk Image" height = 200 width = 600>
</p>
</br>
 
The purpose of the analysis challenge is to generate a supervised machine learning model that will predict the status of a loan, as healthy loans (class 0) or high-risk loans (class 1). The analysis utilizes a logistic regression as a binary classifier for our model. The analysis conducted was on financial data, focusing on loan size, debt-to-income ratio, borrower income, number of accounts, derogatory marks, interest rate, and total debt. 

## Results of the Analysis

 Below is a description of logistic regression model accuracy, precision, and recall scores that the analysis produced.

 * Accuracy: The overall accuracy of the model is 0.99, indicating that it correctly classifies 99% of the instances analyzed.

 * Precision
   * Healthy Loan classified as (class 0): 1.00
   * High-Risk Loan classified as (class 1): 0.85
  
 * Recall
   * Healthy Loan classified as (class 0): 0.99
   * High-Risk Loan classified as (class 1): 0.91 

## Summary

The logistic regression model performs very well in predicting healthy loans (class 0), achieving a precision of 1.00 and recall of 0.99. For risky loans (class 1), the model’s performance is still strong, with a precision of 0.85 and a recall of 0.91.

The slightly lower precision and recall for predicting risky loans may be due to our imbalanced dataset, as there are only 619 risky loans in the test data compared to 18,765 healthy ones. This imbalance limits the number of high-risk loan cases the model can learn from, leaving room for improvement. Adding more examples of risky loans to the training set could help enhance the model’s accuracy for this category.

When classifying loans, prioritizing the identification of high-risk loans is crucial, as the potential financial loss from a loan that defaults is typically greater than the interest earned on a successful loan. The model’s overall accuracy is high, at 99%

### Resources

Module 20

Chat GBT

Picture: https://www.neugroup.com/an-early-warning-system-to-flag-excessive-counterparty-credit-risk/