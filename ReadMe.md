# 🚀 Data Science & Analytics: Advanced Internship Tasks

[cite_start]This repository contains the completion of advanced data science tasks for the **DevelopersHub Corporation** internship[cite: 1, 5]. [cite_start]The projects cover classification with Explainable AI (XAI), unsupervised clustering, and time-series forecasting using industry-standard libraries[cite: 7, 9].

## 📑 Table of Contents
1. [Task 1: Term Deposit Subscription Prediction](#-task-1-term-deposit-subscription-prediction)
2. [Task 3: Energy Consumption Forecasting](#-task-3-energy-consumption-forecasting)
3. [Task 2: Customer Segmentation](#-task-2-customer-segmentation)
4. [Installation & Setup](#-installation--setup)

---

## 📊 Task 1: Term Deposit Subscription Prediction
### 🎯 Objective
[cite_start]Predict whether a bank customer will subscribe to a term deposit based on marketing campaign data[cite: 11, 13].

### ⚙️ Approach
* [cite_start]**Data Acquisition**: Utilized the Bank Marketing Dataset from the UCI Machine Learning Repository[cite: 15].
* [cite_start]**Preprocessing**: Encoded categorical features and split the data for training and testing[cite: 17, 18].
* [cite_start]**Modeling**: Developed classification models, including Random Forest and Logistic Regression[cite: 18].
* [cite_start]**Explainable AI (XAI)**: Implemented **SHAP** to interpret model predictions and identify key features influencing customer behavior[cite: 20, 24].

### ✅ Results
* The Random Forest model provided higher accuracy and F1-scores compared to baseline models.
* SHAP analysis revealed that "call duration" and "previous campaign outcome" were the strongest predictors of subscription.
---

## 🛍️ Task 2: Customer Segmentation
### 🎯 Objective
[cite_start]Cluster customers based on spending habits to propose data-driven marketing strategies[cite: 26, 28].

### ⚙️ Approach
* [cite_start]**EDA**: Conducted Exploratory Data Analysis on the Mall Customers Dataset[cite: 30, 31].
* [cite_start]**Clustering**: Applied **K-Means Clustering** to segment customers into distinct groups[cite: 32].
* [cite_start]**Dimensionality Reduction**: Used **PCA** to visualize high-dimensional clusters in a 2D space[cite: 33, 37].

### 💡 Business Insights
* [cite_start]**Premium Segment**: High income and high spending; recommended for exclusive loyalty rewards[cite: 34, 39].
* [cite_start]**Value Segment**: Low income but high spending; targeted with trend-based promotions[cite: 34].
* [cite_start]**Conservative Segment**: High income but low spending; targeted with high-value investment offers[cite: 34].

---

## ⚡ Task 3: Energy Consumption Forecasting
### 🎯 Objective
[cite_start]Forecast short-term household energy usage using historical time-based patterns[cite: 40, 42].

### ⚙️ Approach
* [cite_start]**Data Resampling**: Parsed and resampled the Household Power Consumption Dataset to a daily frequency[cite: 44, 45].
* [cite_start]**Feature Engineering**: Created time-based features such as hour of day and weekday/weekend indicators[cite: 46, 51].
* [cite_start]**Modeling**: Compared performance between ARIMA, Prophet, and **XGBoost** models[cite: 47].
* [cite_start]**Evaluation**: Assessed model accuracy using MAE and RMSE metrics[cite: 52].

### ✅ Results
* The model successfully captured daily and weekly seasonality in energy consumption.
* XGBoost performed exceptionally well in capturing non-linear spikes during peak usage hours.

---

## 🛠️ Tools & Libraries
* [cite_start]**Languages**: Python [cite: 86]
* [cite_start]**Libraries**: pandas, numpy, scikit-learn, xgboost, shap, matplotlib, seaborn, and Prophet [cite: 9]

---

## 🚀 Installation & Setup
1. Clone this repository to your local machine.
2. Install the required dependencies:
```bash
pip install -r requirements.txt
