# Telecom Churn Prediction

## Abstract
Customer churn has been an important topic in the telecom industry because it directly affects company’s profitability. Churn describes that customers stop using a company’s product or service during a certain time frame. This project aims to predict whether a telecom customer will churn so that telecom companies can take actions to retrain their customers. The specific models used are random forest, gradient boosting machine, logistic regression and KNearest Neighbors.

## Dataset 
The telecom customer churn data was used here is originally provided by the IBM Watson Analytics and available in Kaggle. Downloaded from Kaggle(https://www.kaggle.com/blastchar/telco-customer-churn), the telecom customer churn dataset contains 7043 rows (customers) and 21 columns (features). Each row represents a customer and includes information about customers who left within the last month, services that each customer has signed up for such as phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies. It also includes demographic info about customers such as gender, age range, and if they have partners and dependents. The target column is “Churn” which has binary values, ‘Yes’ or ‘No’. 

## Data Dictionary 
- **Customer ID**: unique customer ID
- **Gender**: gender of a customer
- **Senior Citizen**: if a customer is a senior citizen
- **Partner**: if a customer has a partner
- **Dependents**: if a customer has dependents
- **Tenure**: if a customer is a tenure
- **Phone Service**: if a customer sign up for phone service
- **Multiple Lines**: if a customer sign up for multiple lines
- **Internet Service**: if a customer sign up for internet service
- **Online Security**: if a customer sign up for online security
- **Online Backup**: if a customer sign up for online backup
- **Device Protection**: if a customer sign up for device protection
- **Tech Support**: if a customer sign up for tech support
- **Streaming TV**: if a customer sign up for streaming TV
- **Streaming Movies**: if a customer sign up for streaming movies
- **Contract**: if a customer has a contract with the company
- **Paperless Billing**: if a customer sign up for paperless billing
- **Payment Method**: a customer’ payment method
- **Monthly Charges**: a customer’ monthly charge
- **Total Charges**: a customer’s total charges
- **Churn**: if a customer leave the company

### If unbale to view the notebook in Github
Please use the below link to view the notebook if you are receiving the 'Sorry, soemthing went wrong. Reload?' error message.
https://nbviewer.jupyter.org/github/Jieer334/Telecom-Churn-Prediction/blob/main/Telecom%20Churn%20Prediction.ipynb
