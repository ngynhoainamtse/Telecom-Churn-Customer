# Telecom-Churn-Customer

@author: Nguyen Hoai nam

In this projet, I want to identify customers that are likely to leave and target them in campagnes in the field of telecommunication. 

The question that I want to answer throughtout this work is : **Will the customer churn within 1 month?** 

In this dataset, the time frame was preset to 1 month because the predictive variable "Churn" is defined as followed: 

**Churn = Yes if customers who left within the last month; No otherwise.**

## Data

The data can be found on this Kaggle [link](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).

## Using the code

The executable code can be ran from the main.ipynb notebook.

## Python requirements

Python 3.x and all "classic" packages: numpy, matplotlib etc.

## The main points in this notebook are**

1. Selection of relevant variables based on statistical tools
2. The model used is a XGBOOST: The recall for Class 1 is 97% on the training set and 89% on the test set.
3. For simplicity, cross-validation was not implemented for parameter optimization.