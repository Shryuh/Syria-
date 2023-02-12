# Syria-
SYRIATEL CUSTOMER CHURN


![tel4](https://user-images.githubusercontent.com/116766865/218323330-043595d9-6836-4753-86f6-11dd20452e9f.jpg)


1. INTRDUCTION
SyriaTel is a telecommunications company. They primarily deal with telecommunications of which other companies do business with them. Like other businesses, there are other telecommunication companies making the competition high. Because of the many companies offering different services and having different prices many customers use the services of other companies. As a result, customers may end not using SyriaTel telecommunications company services, resulting in financial losses of the company. This issue disproportionately affects SyriaTel telecommunications company..

2. BUSINESS PROBLEM
The Problem statement
The goal of this project is to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company

Main Objective
This project predicts whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company.

3. NOTEBOOK STRUCTURE
The notebook is here The python notebook is structured as follows:

Data cleaning
Exploratory Data Analysis
Feature selection
Data Modelling and evaluation
4. DATA UNDERSTANDING
The Data
The data used in this project was downloaded from Kaggle and these are the features.

state   : The state in which a person is                   
account length :  The account length  a person has         
area code  :The state in which a person is                  
phone number  :The phone number a person has                 
international plan  :The international plan a person has         
voice mail plan :The voice mail plan a person has          
number vmail messages  :The number vmail messages a person has   
total day minutes :The total day minutes used   
total day calls :The total day calls made               
total day charge :The total charge the company charges during the day      
total eve minutes :The total eve minutes used         
total eve calls :The total eve calls made  
total eve charge :The total charge the company charges at eve
total night calls :The total night  calls made    
total night minutes :The total night minutes used      
total night charge  :The total charge the company charges at night     
total intl minutes :The total international minutes used   
total intl calls :The total international calls made              
total intl charge :The total charge the company charges on international calls      
customer service calls : The customer service calls the company has   
churn : The evaluation of a company's customer loss rate in order to reduce it.

Data Preparation
The data was checked for missing values and were found to have no null values. Columns were not in their appropriate data type so this was easier to work with dataframe. We also had no duplicates in the data.

Exploratory Data Analysis
By carrying out EDA on the cleaned data as seen in this notebook, various patterns were discovered in the dependent and independent variables.. This analysis made it possible to understand how the value of the dependent variable changes as the value of any of the independent variables change.

![syria6](https://user-images.githubusercontent.com/116766865/218322589-1a2ca6eb-6cb5-45ec-82a6-4485cdfbea48.PNG)


The churn has the highest correlation and number vmail messages has the lowest correlation in value counts

Data Interpretation
In this Project, we are going to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company using various features as churn, total day calls, international plan etc .

5.CONCLUSIONS
Area code has the highest 25%, 50%, 75% quartile

number vmail messages has the lowest 25% and 50% quartile

Area code has the highest mean of 437.18 and customer service calls has the lowest mean of 1.56

total day minutes has the highest standard deviation of 54.46 and total intl charge has the lowest standard deviation of 0.75

Model shows not alot of people who make international calls have international plans.

Model shows alot of people have not subscribed to voice mail plan

Model shows at night the calling charges are high and during the day the charges are low

The model has an accuracy of 94%.

6.RECOMMENDATIONS

SyriaTel telecommunications company should consider customer's area code as it is profitable to the business.

SyriaTel telecommunications company should consider total minutes customer's use as it will reduce money lost making it profitable to the business

When choosing when to make calls customers should consider making calls during the day as charges are low.
