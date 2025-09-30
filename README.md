# Customer-Churn-Analysis-EDA-Project

## Problem Statement:
"There has been a 26.5% churn rate in the telecommunications company, but the contributing factors to this attrition is currently unknown."

---

This repository outlines my exploratory data analysis (EDA) on the customer churn rate in a telcommunications company. This project has been implemented using Python on Google Colab and Google slides to present my findings. 

## Project Objective:
The objective of this project was to analyse the churn rate of customers in a hyopthetical telecommunications company by exporting, cleaning, organising, and then performing EDA on the provided .csv file in Google Colab. The intended outcome was to provide insights as to what factors were contributing to customer churn. 

## Overview of findings:
1. **Contract Type Strongly Influences Churn:** Month-to-month contracts have the highest churn rate (42.7%, 3875 customers, 55% of total), while One-year (11.3%, 1473 customers, 20.9% of total) and Two-year contracts (2.8%, 1695 customers, 24.1% of total) show significantly lower churn. Longer contracts correlate with higher tenure, indicating that encouraging contract upgrades could reduce the overall churn rate of 26.5%.

2. **Social Obiligations Reduce Churn:** Customers with partners or dependents are more likely to stay, exhibiting a 19.6% and 15.4% churn, respectively. In contrast, customers without partners or dependents are more likely to pick month-to-month contracts and churn (2288 chose month-to-month (69% of total) and 31.9% churned compared to 10.9% for customers with a partner and dependents).

3. **Early Tenure is High-Risk:** Churn is highest in the first 0-12 months (47.4%, 1037 customers), dropping significantly with longer tenure (e.g., 6.6% for 60-72 months, 93 customers). This suggests that improving the early customer experience (e.g., onboarding, support) is crucial to prevent early churn, particularly for Month-to-month customers.

4. **Add-On Services and Payment Methods Impact Churn:** Lack of add-ons like Online Security (41.77% churn without vs. 14.64% with) increases churn, while automatic payment methods (e.g., Bank transfer, 16.71% churn) are linked to lower churn than Electronic check (45.29%). Promoting add-ons and automatic payments, especially for Month-to-month customers, can enhance retention.
   
5. **Gender has no effect on churn:** The gender distribution in the data given was equal between males and females across all fields. Additionally, their churn rates (26.2% and 26.9%, respectively), indicating that gender has a very minimal impact of churn. Therefore, target marketing for both genders is unnecessary.
   
6. **Senior Customers without add-ons are more likely to churn:** Seniors who do not have add-ons, such as online security, are more than twice likely to churn compared to Senior Customers who do have online security add-ons (50.4% vs 22.7%, respectively). Bundle offers with online security and/or internet service can be distributed during the onboarding process, especially for more senior individuals. 

---

## Tools Used: 
 - Google Colab - Python 3
 - Google Slides - to create the presentation deck
 - Github - to document adn publish the project 

## Skills:
- Data manipulation
- Data cleaning
- Data analysis & visualisation 
