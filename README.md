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
- Logistic Regression (LR): Achieved an accuracy of 74.71%, providing a baseline performance.
- K-Nearest Neighbors (KNN): Achieved an accuracy of 75.61%.
- Classification and Regression Trees (CART): Achieved an accuracy of 79.88%.
- Random Forest (RF): Achieved an accuracy of 86.19%.
- Support Vector Machine (SVM): Achieved an accuracy of 80.01%.
- XGBoost (XGB): Achieved an accuracy of 88.90%.
- LightGBM: Achieved the highest accuracy of 90.47%.
- CatBoost: Achieved an accuracy of 90.94%, demonstrating strong performance.

# Results and Conclusion:
Among the models trained, CatBoost and LightGBM emerged as the top performers, with accuracies of 90.94% and 90.47%, respectively. These models outperformed other algorithms such as Logistic Regression and KNN, indicating the effectiveness of gradient boosting techniques for this task.

# Files Included:
- Dataset: Contains the dataset used for training and testing the model.
- Model: Includes the trained LightGBM model.
- Notebooks: Jupyter notebooks detailing the data exploration, preprocessing, model development, and evaluation.
- README: This file, providing an overview of the project.
