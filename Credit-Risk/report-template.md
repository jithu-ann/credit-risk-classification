# Module 12 Report Template

## Overview of the Analysis

The purpose of the analysis is to predict the loan is in high risk loan or healthy loan for people by using multiple data's.

loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, loan_status are the financial information we used. we need to predict, was this loan is in high risk or a healthy one.

value_counts is used to check the number of loan status based on high risk and healthy.
For the analysis, split the data into training and testing datasets by using train-test-split. then, create a logistic regression model by using the training data and fit the model using training data, and save the predictions.

## Results

   •The accuracy is 0.99
   •The precision of high risk loan is 0.87
   •The recall of high risk loan is 0.89
   •The precision of healthy loan is 1.00
   •The recall of healthy loan is 1.00
   
   

## Summary

The logical regression model did a good job at predicting the loan status. but this model helps to predict healthy loans better rather than high risk. but in overall, when you look at the accuracy which is 0.99 is good. May be, more data's will be helpful to predict the high risk loan better.
