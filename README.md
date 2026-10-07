# CREDIT DEFAULT RISK PREDICTION

## PROJECT OVERVIEW
This project develops a machine learning system to predict whether a borrower is likely to default on a loan based on their demographic, financial, credit history, and loan characteristics.
The primary goal is not only to achieve high predictive performance, but also to build a model that can effectively identify high-risk borrowers while considering the business cost of incorrect predictions.
The project follows an end-to-end machine learning workflow, including data exploration, preprocessing, feature engineering, handling class imbalance, model development, hyperparameter tuning, evaluation, and model interpretation.

## BUSINESS PROBLEM
Loan default creates significant financial risk for lenders. Before approving a loan, financial institutions need to assess the likelihood that a borrower will fail to repay.

A predictive model can help lenders:
* Identify borrowers with higher default risk
* Prioritize applications for additional review
* Make more consistent, data-driven lending decisions

## INTENDED USE
The model is meant to be used after a loan has been priced, so the interest rate (loan_int_rate) is known. It supports risk assessment at that stage. It is not designed to score raw applicants before a rate has been assigned.

## DATASET

The dataset contains borrower and loan-level information used to predict the target variable:

loan_status

where:

0 → Loan does not default

1 → Loan defaults

The dataset contains approximately 32,000 observations and includes demographic, financial, credit history, and loan-related variables. Some of the features were dropped to remove dependency and add more freedom for risk prediction.
