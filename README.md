# Predicting-Credit-Card-Default-Using-XGBoost

[Link to this project on Kaggle](https://www.kaggle.com/yuankunsong/predicting-credit-card-default-auc-0-793)

## This project aims to analyze credit card default rates. The dataset is from information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

### The method used was XGBoost, with extensive hyperparameter tuning.

### Key findings: the most important factors affecting credit card repayment in a given month are:
* Statement amount in previous month
* Repayment status in previous month
* Amount of payment in previous month

### Feature importance given by the XGBoost Model:
![alt text](https://github.com/charliesong66/Charlie_Song_DataScience_Portfolio/blob/master/images/creditcard1.png?raw=true)

### Building a model using all data but the current month, then validate the model by making prediction on that month acheived an AUC of 0.793. Below is the confusion matrix:
![alt text](https://github.com/charliesong66/Charlie_Song_DataScience_Portfolio/blob/master/images/creditcard2.png?raw=true)
