# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose of the analysis is to develop a model that predicts the likelihood of a loan being classified as healthy or high-risk based on the different features of the loan applicants.

  
* Explain what financial information the data was on, and what you needed to predict.

The financial information was on the specific loan applicants and it is used to predict whether the applicant is high or low risk
  
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

The dataset includes financial information on various loans with loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks on the borrower's credit report, and total debt owed as the features. loan_status is the target varaiable and it indicates whether a loan is healthy or high-risk.

* Describe the stages of the machine learning process you went through as part of this analysis.

The machine learning process involved reading the lending data from the CSV file into a dataframe, setting up the label from loan_status column and the features from the other columns. Then I split the data into training and testing sets fitting a logistic regression model with the training data and making predictions on the test data. Finally I evaluated the model by generating a confusion matrix and printing the classification report.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

  LogisticRegression is the method I used.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1: Logistic Regresssion
   * Accuracy: 0.99
   The model accurately predicted the loan status of 99% of the test data.
   
   * Precision:

   Healthy Loans : 1.00
  
   High Risk : 0.85

  * Recall:

  Healthy : 0.99
  
  High Risk: 0.91


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
