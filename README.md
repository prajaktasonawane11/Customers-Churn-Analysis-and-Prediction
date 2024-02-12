# Banking-Customers-Churn-Prediction
![Customer Churn](https://github.com/prajaktasonawane11/Banking-Customers-Churn-Prediction/blob/main/CustomerChurn.png)

# Overview:
This project aims to develop a machine learning model to predict whether a bank's customers are likely to leave the bank or not. Customer churn, defined as the closing of a customer's bank account, is a critical metric for banks to understand and mitigate. By identifying customers at risk of leaving, banks can take proactive measures to retain them and improve overall customer satisfaction and profitability.

# Dataset:
The dataset consists of 100,000 observations and 12 variables. Here's a brief overview of the variables:

- CreditScore: Higher scores indicate lower risk of churn.
- Geography: Customer location can influence churn behavior.
- Gender: Investigating whether gender plays a role in churn.
- Age: Older customers are typically more loyal.
- Tenure: Longer tenure implies higher loyalty.
- Balance: Customers with higher balances are less likely to churn.
- NumOfProducts: Number of products owned by the customer.
- HasCrCard: Indicates whether the customer has a credit card.
- IsActiveMember: Active customers are less likely to churn.
- EstimatedSalary: Higher salaries may correlate with lower churn.
- Exited: Target variable indicating whether the customer left the bank.

# Model Development:
We used the LightGBM algorithm for this task, a gradient boosting framework that delivers high performance and efficiency. The model was optimized using hyperparameter tuning to maximize accuracy.

# Results:
The final model achieved an accuracy score of 91.16%. This indicates that the model is able to correctly classify customers as churned or retained with high accuracy.

# Files Included:
- Dataset: Contains the dataset used for training and testing the model.
- Model: Includes the trained LightGBM model.
- Notebooks: Jupyter notebooks detailing the data exploration, preprocessing, model development, and evaluation.
- README: This file, providing an overview of the project.
