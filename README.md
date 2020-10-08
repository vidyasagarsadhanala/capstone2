# Springboard DataScience bootcamp - Capstone Project 2 #

## Telco Customer Churn Prediction ## 

### Objective: ###
The objective is to predict customer churn behavior for Telco which is a telecommunications service provider so they can better retain their customers by analyzing all relevant customer data and develop focused customer retention programs.

 
### Problem: ###
Is the customer going churn?

### Outcome: ###
When a customer stops service or company losing customer is referred to as Customer Churn. This is an important measure for any service-based company. The model predictions an provide the propensity of churning and gives the companies with the feature’s importance that leads the customer to churn. With the list of potential customers who are likely to churn, the marketing/retention teams can then take measure to reduce their churn probability. This project helps companies in identifying customer who are at risk of churning and we have used this IBM sample data set provided for a telecom company. We will be using statistical analysis to understand variables that are associated with customer churn.

### Dataset: ###
*	Customers who left within the last month – the column is called Churm
*	Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
*	Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
*	Demographic info about customers – gender, age range, and if they have partners and dependents

### Data Wrangling ###
* Total Charges variable is an object data type so had to convert it into a numerical data type for analysis 
* Converted Churn variable to numerical data type for analysis
*Total Charges variable contains missing or null values, so imputing them with means and used SimpleImputer from Sklearn.impute

### Exploratory Data Analysis ###
* More customers are using Fiber Optic for Internet Service have left the company than compared to DSL.
* Customers who do not use online security have left the company.
* Customers not using technical support have left the company.
* Customers who pay month to month are the most who leave the company.
* Customer's gender has almost equal rates of churn between them.
* The Monthly Charges for customer's who churned tends to pay higher monthly fees than those that stay.
* Customers that churn tend to be relatively new customers when looking at tenure distribution.

### Machine Learning ###
'''
Insert txt here.
'''
### Conclusion ###
'''
Insert txt here.
'''
