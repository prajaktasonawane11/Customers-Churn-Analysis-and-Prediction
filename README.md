# Banking-Customers-Churn-Prediction
![Customer Churn](https://github.com/prajaktasonawane11/Banking-Customers-Churn-Prediction/blob/main/CustomerChurn.png)

# Overview:
This project aims to develop a machine learning model to predict whether a bank's customers are likely to leave the bank or not. Customer churn, defined as the closing of a customer's bank account, is a critical metric for banks to understand and mitigate. By identifying customers at risk of leaving, banks can take proactive measures to retain them and improve overall customer satisfaction and profitability.

# Dataset:
The dataset consists of 10,000 observations and 12 variables. Here's a brief overview of the variables:

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

# Model Development and Evaluation:
- Gradient Boosting has the highest F1 score (0.598391) and the highest ROC AUC score (0.859767) among all the models. This suggests that Gradient Boosting is the most effective model in balancing precision and recall and has the best ability to distinguish between the churned and non-churned customers.
- XGBoost also performs well, with a relatively high F1 score (0.586974) and a good ROC AUC score (0.841784). This indicates that XGBoost is another strong model for this task.
- Random Forest has a high accuracy (0.862000) but a lower F1 score (0.538976) compared to Gradient Boosting and XGBoost. This suggests that while Random Forest is good at predicting the majority class (non-churned customers), it might not be as effective at identifying the minority class (churned customers).
- Support Vector Machine and K-Nearest Neighbors have moderate F1 scores and ROC AUC scores. They perform better than Logistic Regression but are not as effective as Gradient Boosting or XGBoost for this dataset.
- Logistic Regression has the lowest accuracy (0.703667), F1 score (0.473029), and ROC AUC score (0.764076) among all the models. This indicates that Logistic Regression is the least effective model for predicting customer churn in this dataset.

# Dashboard:
![Dashboard](https://github.com/prajaktasonawane11/Customers-Churn-Analysis-and-Prediction/blob/main/Customer_Churn_Dashboard.png)

# Files Included:
- Dataset: Contains the dataset used for training and testing the model.
- Notebooks: Jupyter notebooks detailing the data exploration, preprocessing, model development, and evaluation.
- Tableau Dashboard file and the Screenshot of the Dashboard.
- README: This file, providing an overview of the project.
