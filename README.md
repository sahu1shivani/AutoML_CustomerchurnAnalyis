# Bank Churn Modeling - README

## Background
Banks are keen to retain their valuable clients. They often focus on attracting new customers initially but eventually need to adopt a defensive approach to maintain their existing clientele. Even with excellent user experiences, a percentage of customers may decide to leave. The challenge is how to effectively prevent these voluntary exits, and a churn model can assist in addressing this.

## Abstract
This repository contains data related to a bank's clients, with the binary target variable indicating whether a client has remained with the bank or closed their account. The primary objective is to implement AutoML using H2O and analyze the churn modeling dataset. We aim to answer several questions:

1. Is the relationship significant?
2. Are any model assumptions violated?
3. Is there any multicollinearity in the model?
4. Are predictor variables independent in multivariate models?
5. Rank the most significant predictor variables and exclude insignificant ones.
6. Does the model make sense?
7. Does regularization improve the model?
8. Which independent variables are significant?
9. Which hyperparameters are important?

We will explore these questions through data analysis and the use of AutoML, a tool provided by H2O.ai, to train and predict in various models. Finally, we will assess and print the performance of the best model.

## Dataset Information
**Dependent Variable/Target Variable:**
- Exited: A binary flag (1 or 0) indicating if the customer closed their account with the bank (1) or remained a customer (0).

**Independent Variable/Predictor Variables:**
1. CustomerId: A unique identification number for each customer.
2. Surname: The customer's last name.
3. CreditScore: The credit score of the customer.
4. Geography: The country from which the customer hails.
5. Gender: The customer's gender (Male or Female).
6. Age: The age of the customer.
7. Tenure: The number of years the customer has been with the bank.
8. Balance: The bank balance of the customer.
9. NumOfProducts: The number of bank products the customer is utilizing.
10. HasCrCard: A binary flag indicating whether the customer has a credit card (1) or not (0).
11. IsActiveMember: A binary flag indicating whether the customer is an active member with the bank (1) or not (0).
12. EstimatedSalary: The estimated salary of the customer in Dollars.

This dataset is essential for understanding customer behavior and developing strategies to reduce churn. The analysis in this repository aims to provide valuable insights and solutions for the banking industry.

## Conclusion:
In this notebook, we examined how H2O AutoML can be used to:

1. Describe a dataset
2. Train models with minimal human inputs
3. Make predictions on a trained model
4. Explain the model’s predictions

## References:
1. H2O.AI
2. Youtube: H2o
