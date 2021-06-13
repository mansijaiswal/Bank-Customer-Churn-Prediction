# Bank Customer Churn Prediction
## Classification Model

### Team Members:
* Anupriya Sharma
* Mansi Jaiswal
* Ritu Malpani

### Objective:
The objective of this project is to draw meaningful insights from the data and find the possible reasons leading to customer churn from the bank. We wish to develop a classification model which predicts whether a customer will leave the bank or not on the basis of the several explanatory variables given in the dataset.

It is very important to reduce churn since the cost incurred to retain a customer is lower than the cost incurred to acquire a new one.
Upon knowing the factors contributing to churn, the bank could improve upon its services and reduce churn. The model will help the bank to know the probability of a customer leaving the bank apriori and could take necessary steps to retain a customer with a higher probability of churning out.

### Tool:
Python will be used as the programming language.

### Dataset:
The dataset has been collected from Kaggle. The link is given below:

https://www.kaggle.com/mathchi/churn-for-bank-customers

### Data Description:
* RowNumber — corresponds to the record (row) number
* CustomerId — contains random values
* Surname — the surname of a customer
* CreditScore — the credit score of an individual
* Geography — a customer’s location
* Gender — Male/Female
* Age — age of the customer
* Tenure — refers to the number of years that the customer has been a client of the bank
* Balance — account balance 
* NumOfProducts — refers to the number of products that a customer has purchased through the bank.
* HasCrCard — denotes whether or not a customer has a credit card
* IsActiveMember — whether the customer is active or not (0/1)
* EstimatedSalary — salaries of the customers
* Exited — whether or not the customer left the bank

### Hypothesis:
* Do people with 0.00 account balance have higher probability of leaving the bank?
* Does Gender affect churn?
* Are customers with low credit score more likely to churn?
* Does number of products purchased by customer affect churn?
* Does customer's location affect their decision of leaving the bank?
* Is younger generation more likely to churn?
* Is inactiveness of a member sign of their churn?
* Does the number of years the customer has been a client of the bank affect churn?
* Are customers with low salary more likely to churn?
* Are people with a credit card less likely to leave the bank?

### Discussion Notes
#### 27.05.2021
* Perform EDA on the dataset
* Search for the various statistical tests which can be applied
* Check the assumptions of the test
* Check what possible models can be used and what are the assumptions

### Plan of action
We now wish to work on the following aspects:
* Deciding the metric to be used
* Building a logistic regression model and checking it's assumptions
* Building a decision tree
* Comparing the 2 models with respect to the metric
