# Logistic-regression-model-bank-cards-operations-
Logistic regression model (bank cards operations)

# Introduction
Logistic regression is algorithm of classification machine learning. Model predicts binary state of dependent variable. Dependent result variable takes value from 0 to 1.
Main principles of logistic regression model
Dependent variable has a binary form.
Model contain only variables who have significant influence on the result.
There are no collinearity among independent variables (no correlation among predictors).
Logistic model needs big number of observations.
Let's open data with needed libraries. We will be working on the registry of bank cards operations. In colum 'Class' value 0 mean: lack of fraud in transaction, value 1 point embezzlement. Let's take an assumption, main aim is to correctly classification of transactions with embezzlement. We can unfortunately certificate good transaction as the transaction with fraud.
