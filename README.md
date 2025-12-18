![professional-analyzing-customer-churn-digital-screen-highlighting-lost-clients-active-user-base-addressing-309095824](https://github.com/user-attachments/assets/cb0ff497-052b-4457-9825-aaf5a1bef2df)

# Telecom_Customer_Churn_Prediction

In the increasingly competitive telecommunications sector, customer retention has become a critical priority. Customer churn, defined as customers discontinuing their service and switching to alternative providers, poses a significant challenge as it directly affects revenue and long-term business sustainability. This project aims to develop a predictive model capable of identifying customers who are at high risk of churning by analyzing their service usage patterns, behavioral characteristics, and subscription details. By uncovering these patterns, telecom companies can take proactive measures to enhance customer satisfaction and minimize churn rates.

This repository provides a comprehensive framework for customer churn analysis, encompassing the dataset, data preprocessing steps, and machine learning models used for prediction. In addition to predictive modeling, the project delivers data-driven insights into the key factors influencing customer attrition and proposes strategic recommendations to support telecom companies in strengthening customer retention efforts. For a concise overview of the project.

---

## Problem Statement

today have multiple service providers to choose from, and even minor issues such as service interruptions, poor technical support, or pricing dissatisfaction can lead them to switch providers.

Customer acquisition is significantly more expensive than customer retention, making churn a direct threat to revenue and long-term business sustainability. Understanding why customers leave, identifying high-risk churn segments, and acting proactively are critical for telecom companies to maintain profitability and customer trust.

Therefore, analyzing customer behavior and service usage patterns to predict churn is a vital step toward designing effective retention strategies and improving service quality.

---

## Aim

The goal of this project is to identify and classify customers who are likely to churn by utilizing both numerical and categorical data. This involves solving a binary classification problem while carefully handling the inherent imbalance in the dataset.

---

## Dataset Overview

The Telco Customer Churn dataset contains information about customers, their demographics, account details, and services they have subscribed to. It is designed to help predict customer churn, i.e., whether a customer is likely to leave the telecom company.

The dataset includes 21 columns grouped into 4 main categories: Target, Customer Demographics, Account Information, and Services Subscribed.

| Column Name          | Description                                                                                                                 |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| **customerID**       | Unique identifier for each customer.                                                                                        |
| **gender**           | Whether the customer is male or female.                                                                                     |
| **SeniorCitizen**    | Whether the customer is a senior citizen or not (`1 = Yes, 0 = No`).                                                        |
| **Partner**          | Whether the customer has a partner (`Yes` or `No`).                                                                         |
| **Dependents**       | Whether the customer has dependents (`Yes` or `No`).                                                                        |
| **tenure**           | Number of months the customer has stayed with the company.                                                                  |
| **PhoneService**     | Whether the customer has a phone service (`Yes` or `No`).                                                                   |
| **MultipleLines**    | Whether the customer has multiple lines (`Yes`, `No`, `No phone service`).                                                  |
| **InternetService**  | Customer’s internet service provider (`DSL`, `Fiber optic`, `No`).                                                          |
| **OnlineSecurity**   | Whether the customer has online security (`Yes`, `No`, `No internet service`).                                              |
| **OnlineBackup**     | Whether the customer has online backup (`Yes`, `No`, `No internet service`).                                                |
| **DeviceProtection** | Whether the customer has device protection (`Yes`, `No`, `No internet service`).                                            |
| **TechSupport**      | Whether the customer has tech support (`Yes`, `No`, `No internet service`).                                                 |
| **StreamingTV**      | Whether the customer has streaming TV (`Yes`, `No`, `No internet service`).                                                 |
| **StreamingMovies**  | Whether the customer has streaming movies (`Yes`, `No`, `No internet service`).                                             |
| **Contract**         | The contract term of the customer (`Month-to-month`, `One year`, `Two year`).                                               |
| **PaperlessBilling** | Whether the customer uses paperless billing (`Yes` or `No`).                                                                |
| **PaymentMethod**    | The customer’s payment method (`Electronic check`, `Mailed check`, `Bank transfer (automatic)`, `Credit card (automatic)`). |
| **MonthlyCharges**   | The amount charged to the customer monthly.                                                                                 |
| **TotalCharges**     | The total amount charged to the customer over their tenure.                                                                 |
| **Churn**            | Whether the customer has churned (`Yes` or `No`).                                                                           |

---

##أكيد 👍
دي **نسخة مُعاد صياغتها بشكل احترافي وواضح**، مناسبة جدًا للـ **README أو التقرير الأكاديمي**، مع الحفاظ على نفس المعنى لكن بلغة أبسط وأقوى:

---

## Objectives

The main objective of this project is to build a reliable predictive model that can identify customers who are likely to churn by utilizing both numerical and categorical features. This problem is treated as a binary classification task while accounting for the class imbalance present in the dataset.

1. Dataset Understanding and Feature Exploration:
   To thoroughly examine the dataset and its attributes, including customer identifiers, demographic information, senior citizen status, partnership, dependents, tenure, and subscribed         services.

2. Customer Profile Analysis:
   To analyze customer characteristics by exploring demographic details, service usage patterns, contract types, billing preferences, and payment methods.

3. Internet and Service Usage Evaluation:
   To investigate the availability of internet services and related features such as online security, online backup, device protection, technical support, streaming TV, and streaming           movies, and assess their relationship with customer churn.
   
5. Contract and Billing Behavior Analysis:
   To examine the impact of contract terms, billing methods, paperless billing preferences, and monthly and total charges on customer retention.

6. Churn Analysis and End-to-End Modeling Workflow:
   To analyze customer churn through a complete data science pipeline, including dataset exploration, exploratory data analysis (EDA), feature engineering, model development, evaluation,       and final conclusions.

---




















