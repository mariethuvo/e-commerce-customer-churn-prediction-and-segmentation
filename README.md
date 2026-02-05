## E-commerce Customer Churn Analysis & Prediction
# 📌 Project Overview

This project analyzes customer churn behavior for an e-commerce company and builds machine learning models to predict churned users.
The objective is to help the business reduce churn by understanding user behavior, identifying churn risk factors, and designing targeted retention and promotional strategies.

The project combines:

* Exploratory Data Analysis (EDA)

* Supervised Learning (Churn Prediction)

* Unsupervised Learning (Churned User Segmentation)

# 🎯 Business Problem

Customer churn directly impacts revenue, customer lifetime value, and growth sustainability.
The company wants to:

* Understand why users churn

* Predict which users are likely to churn

* Segment churned users to design personalized promotions

# 🗂 Dataset Description

The dataset (churn_predict.csv) contains customer-level behavioral, demographic, and transactional features.

Key Variables

CustomerID – Unique customer identifier

Churn – Churn flag (1 = churned, 0 = active)

Tenure – Customer tenure

PreferredLoginDevice – Preferred login device

CityTier – City tier (1, 2, 3)

WarehouseToHome – Distance from warehouse to customer

PreferPayment – Preferred payment method

Gender – Customer gender

HourSpendOnApp – Time spent on app / website

NumberOfDeviceRegistered – Registered devices

PreferedOrderCat – Preferred order category

SatisfactionScore – Customer satisfaction score

MaritalStatus – Marital status

NumberOfAddress – Number of saved addresses

Complain – Complaint raised in the last month

# 🔍 Exploratory Data Analysis (EDA)

The EDA focused on identifying behavioral patterns of churned users, including:

* Lower satisfaction scores

* Higher complaint frequency

* Differences in tenure, engagement time, and device usage

* Behavioral differences across payment methods and order categories

# 📌 Key Insights

* Customer dissatisfaction and complaints are strong churn indicators

* Shorter tenure users show higher churn risk

* Engagement metrics (time spent, devices registered) differ significantly between churned and active users

💡 Business Recommendations

* Improve service recovery for customers who submit complaints

* Introduce early-stage engagement programs for new users

* Personalize promotions based on user behavior and preferences

# 🤖 Supervised Learning: Churn Prediction

Built machine learning models to predict churned users based on customer behavior and attributes.

Approach

Data preprocessing and feature encoding

Train/test split

Model evaluation using classification metrics

Goal

Enable the business to proactively identify churn-risk users and intervene before churn occurs.

# 🧠 Unsupervised Learning: Churned User Segmentation

To support targeted promotions, churned users (Churn = 1) were segmented using KMeans clustering.

Objective

Group churned users based on behavioral similarities

Identify distinct churn profiles

Tailor re-engagement strategies for each segment

Outcome

Identified multiple churned user segments with differences in:

Engagement level

Satisfaction and complaint behavior

Usage patterns and preferences

These insights enable personalized win-back campaigns instead of one-size-fits-all promotions.
