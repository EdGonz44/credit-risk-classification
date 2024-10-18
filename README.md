# credit-risk-classification
Module 20 Project

## Overview of the Analysis
The purpose of this analysis was to determine if a logistical regression model could act effectively at predicting the financial security in approving a loan. This involved taking into account the various features involved in the borrower's profile (loan size, interest rate, income, debt/income proportion, number of accounts, derogatory marks, and total debt), and the actual loan status that would be determined through taking into account the features. The loan status is detailed as 0 (healthy) or 1 (high-risk), and is meant to be taken into account in approving or denying a loan. The machine learning model used involved splitting the financial records into a training and testing datasets, and then running these through a logistical regression model. The jupyter notebook conducting this analysis can be accessed here: [Credit-Risk-Analysis](https://github.com/EdGonz44/credit-risk-classification)


## Results
Logistical Regression Model

- Healthy Loan Precision: 1.00
- Healthy Loan Recall: 0.99
- High-Risk Loan Precision: 0.84
- High-Risk Loan Recall: 0.94
- Accuracy: 0.99

## Summary
This logistic regression model appears to do very well in predicting a possible healthy loan, but falls a little short in predicting a high-risk loan. This can be seen in that every loan predicted to be healthy was indeed healthy, but only 84% percent of the predicted high-risk loans were actually high-risk. This is a preferred outcome however, as it would be preferential to be able to always predict a safe loan, as this means no loss will be made. 

On the other hand, incorrectly predicting a high-risk loan would mean that the loan would actually be safe, but still declined; this is still a preferred outcome, for while we would lose possible profit, we would more likely be declining a loan that would have a high risk of defaulting, creating a loss in profit.

Overall, this model can be deemed useable, as it ensures that safe loans are always approved while losing out on possible profit through false negatives.
