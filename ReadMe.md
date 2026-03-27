# 🚀 Data Science & Analytics: Advanced Internship Tasks

This repository contains the completion of advanced data science tasks for the **DevelopersHub Corporation** internship. The projects cover classification with Explainable AI (XAI), unsupervised clustering, and time-series forecasting.

## 📑 Table of Contents
1. [Task 1: Term Deposit Subscription Prediction](#-task-1-term-deposit-subscription-prediction)
2. [Task 2: Customer Segmentation](#-task-2-customer-segmentation)
3. [Task 3: Energy Consumption Forecasting](#-task-3-energy-consumption-forecasting)
4. [Installation & Setup](#-installation--setup)

---

## 📊 Task 1: Term Deposit Subscription Prediction
### 🎯 Objective
Predict whether a bank customer will subscribe to a term deposit based on marketing campaign data.

### ⚙️ Approach
* **Data Acquisition**: Utilized the Bank Marketing Dataset from the UCI Machine Learning Repository.
* **Preprocessing**: Encoded categorical features and split the data for training and testing.
* **Modeling**: Developed classification models, including Random Forest and Logistic Regression.
* **Explainable AI (XAI)**: Implemented **SHAP** to interpret model predictions and identify key features influencing customer behavior.

### ✅ Results
* The Random Forest model provided higher accuracy and F1-scores compared to baseline models.
* SHAP analysis revealed that "call duration" and "previous campaign outcome" were the strongest predictors of subscription.

---

## 🛍️ Task 2: Customer Segmentation
### 🎯 Objective
Cluster customers based on spending habits to propose data-driven marketing strategies.

### ⚙️ Approach
* **EDA**: Conducted Exploratory Data Analysis on the Mall Customers Dataset.
* **Clustering**: Applied **K-Means Clustering** to segment customers into distinct groups.
* **Dimensionality Reduction**: Used **PCA** to visualize high-dimensional clusters in a 2D space.

### 💡 Business Insights
* **Premium Segment**: High income and high spending; recommended for exclusive loyalty rewards.
* **Value Segment**: Low income but high spending; targeted with trend-based promotions.
* **Conservative Segment**: High income but low spending; targeted with high-value investment offers.

---

## ⚡ Task 3: Energy Consumption Forecasting
### 🎯 Objective
Forecast short-term household energy usage using historical time-based patterns.

### ⚙️ Approach
* **Data Resampling**: Parsed and resampled the Household Power Consumption Dataset to a daily frequency.
* **Feature Engineering**: Created time-based features such as hour of day and weekday/weekend indicators.
* **Modeling**: Compared performance between ARIMA, Prophet, and **XGBoost** models.
* **Evaluation**: Assessed model accuracy using MAE and RMSE metrics.

### ✅ Results
* The model successfully captured daily and weekly seasonality in energy consumption.
* XGBoost performed well in capturing non-linear spikes during peak usage hours.

---

## 🛠️ Tools & Libraries
* **Languages**: Python
* **Libraries**: pandas, numpy, scikit-learn, xgboost, shap, matplotlib, seaborn, and Prophet

---

## 🚀 Installation & Setup
1. Clone this repository to your local machine.
2. Install the required dependencies:
```bash
pip install -r requirements.txt
