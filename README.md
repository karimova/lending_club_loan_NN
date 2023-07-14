# Loan Default Prediction
<img src="p-2.jpg" alt="loan" width="600">

## Problem Statement
For companies like Lending Club, accurately predicting whether a loan will default is of utmost importance. In this project, using historical data from 2007 to 2015, we aim to build a deep learning model that predicts the likelihood of default for future loans. The dataset is highly imbalanced and includes numerous features, making this problem particularly challenging.

## Domain
Finance

## Analysis to be Done
Perform data preprocessing and build a deep learning prediction model.

## Dataset
The dataset contains the following columns and their definitions:

- `credit.policy`: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
- `purpose`: The purpose of the loan (values include "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").
- `int.rate`: The interest rate of the loan, as a proportion.
- `installment`: The monthly installments owed by the borrower if the loan is funded.
- `log.annual.inc`: The natural log of the self-reported annual income of the borrower.
- `dti`: The debt-to-income ratio of the borrower.
- `fico`: The FICO credit score of the borrower.
- `days.with.cr.line`: The number of days the borrower has had a credit line.
- `revol.bal`: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
- `revol.util`: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).
- `inq.last.6mths`: The borrower's number of inquiries by creditors in the last 6 months.
- `delinq.2yrs`: The number of times the borrower has been 30+ days past due on a payment in the past 2 years.
- `pub.rec`: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).

## Steps to Perform

1. Feature Transformation: Convert categorical values into numerical values (discrete).

2. Exploratory Data Analysis: Perform an exploratory data analysis of different factors in the dataset.

3. Additional Feature Engineering: Check the correlation between features and drop those with strong correlations. This will reduce the number of features and leave us with the most relevant ones.

4. Modeling: After EDA and feature engineering, we will build a deep learning model using Keras with the Tensorflow backend.



4.     Modeling

After applying EDA and feature engineering, you are now ready to build the predictive models

In this part, you will create a deep learning model using Keras with Tensorflow backend
