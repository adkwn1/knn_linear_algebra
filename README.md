## K-Nearest Neighbor Classification and Linear Algebra in Regession Tasks
Author: Andrew Kwon

## Description
This project covers a few linear algebra concepts. We first evaluate a classification model using the k-nearest neighbor algorithm. The prediction model is trained using the original data as well as scaled data (MaxAbsScaler) in order to compare performance differences. Models evaluated based on F1 score. Additionally, the project conducts an analytical proof for the use of matrix operations to obfuscate data in regression tasks. Data analysis and solution code conducted in Jupyter notebook.

## Introduction
Using machine learning and a set of client data from an insurance company, we are to solve the following tasks:
- Task 1: Find customers who are similar to a given customer. This will help the company's agents with marketing.
- Task 2: Predict whether a new customer is likely to receive an insurance benefit. Can a prediction model do better than a dummy model?
- Task 3: Predict the number of insurance benefits a new customer is likely to receive using a linear regression model.
- Task 4: Protect clients' personal data without breaking the model from the previous task. You don't need to pick the best model, just prove that the algorithm works correctly.

## Dataset
**insurance_us.csv**
- *Gender*: Gender of the insured client.
- *Age*: Client's age.
- *Salary*: Client's salary.
- *Family Members*: Number of family members insured under the client.
- *Insurance Benefits*: Number of benefits claimed by the insured person in the last five years.

## Requirements
- numpy
- pandas
- math
- seaborn
- sklearn.linear_model
- sklearn.metrics
- sklearn.preprocessing
- sklearn.model_selection
- sklearn.neighbors
