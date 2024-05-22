# Churn Predictor System
# Overview
## Executive Summary:
This project proposal details the deployment of a customer churn prediction system for the Sales and Marketing department. By harnessing machine learning and data analytics capabilities, the system seeks to tackle critical obstacles and tap into substantial growth prospects, leading to improved profitability and heightened customer satisfaction.

# Business Understanding
A telco company that has alot of its customers who don't remain for long thus the company incurs great losses. They need a model that will help them see patterns and presict customers who are about to stop using their services and thus mitigate it. 

## Problem Statement:
The Sales and Marketing department faces challenges such as:
1.  High churn of cutomers in the company.
2.  Inadequate data on consumer behaviour so as to realise customer retention.
   
## Objectives:
-  Reduce churn and increase profitability bu retaining customers.
-  Having data driven insights will enhance efficiancy.
-  Increase relevance in the market.
  
# Proposed solution

• Implement certain strategies by having offers and reward systems to custmers who have been loyal. 	

•	Make decisions that are informed through data by gaining insights to customer behaviour and preference. 

•Have campaigns and programs that reach specifically to customers. 	

# Data Understanding
-The data was sourced from Kaggle at https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset

## Data Types:
•	Boolean: 1 column (churn)

•	Float: 8 columns (total day minutes, total day charge, total eve minutes, total eve charge, total night minutes, total night charge, total intl minutes, total intl charge)


•	Integer: 8 columns (account length, area code, number vmail messages, total day calls, total eve calls, total night calls, total intl calls, customer service calls)

•	Object: 4 columns (state, phone number, international plan, voice mail plan)

## Data Analysis (EDA)

Exploratory data analysis was implemented inorder to transform the data into information that can used to source data insights. The following methods and technqiues were used to transform the data into information:

  1. Pivot Tables
  2. Feature Engineering
  3. Feature Selection
  4. Lambda functions

## Model Performance

1. Decision Trees Algorithm

The main classification metrics of interest were Precision, Recall and AUC-ROC score, this due the fact that the purpose of the model was to save the stakeholders money through correct classification of customers that are prone to churn. Below is a breakdown to the models performance 

![decision tree](https://github.com/drewbaraka/Phase-3-Project/assets/45417926/5c25a38f-ee66-4009-98d5-35cb8f99aea8)

2. XGB Classifier Algorithm

   The XGB Classifier Algorithm was deemed suitable for this due to it capabilities with handling imbalanced distributions.

## Recommendations

1. Give more attention to customers subscribed to international and voice mail plan by giving promotions and discounts.

2. Implementing targeted customer retention programs so as to reduce churn rates. This can be designing international plan packages that cater to different economic classes.

3. Engaging with customers through feedback mechanisms, such as incentivized surveys, will assist in better pricing, better international plan experiences.




