🚀 Data Science & Analytics: Advanced Internship Tasks
This repository contains the completion of the advanced task set for the Data Science Internship at DevelopersHub Corporation. It covers classification with Explainable AI, unsupervised clustering, and time-series forecasting.
📑 Table of ContentsTask 1: Term Deposit Subscription PredictionTask
2: Customer SegmentationTask
3: Energy Consumption ForecastingInstallation & Setup
📊 Task 1: Term Deposit Subscription Prediction🎯
Objective
Predict whether a bank customer will subscribe to a term deposit as a result of a marketing campaign using classification models and Explainable AI (XAI).
⚙️ Approach
Data Acquisition: Dataset fetched directly from the UCI Machine Learning Repository.
Preprocessing: Categorical features were encoded, and the data was split into training and testing sets.
Modeling: Trained Logistic Regression and Random Forest models.
XAI Integration: Utilized SHAP to interpret model predictions and identify key drivers behind customer decisions.
📈 ResultsThe Random Forest model provided superior predictive power compared to Logistic Regression.SHAP analysis revealed that call duration and age were significant predictors of subscription behavior.
🛍️ Task 2: Customer Segmentation🎯
Objective
Cluster customers based on spending habits and propose tailored marketing strategies.
⚙️ Approach
EDA: Conducted Exploratory Data Analysis to identify initial patterns in income and spending.
Clustering: Applied K-Means Clustering ($k=5$) to segment the Mall Customers dataset.
Visualization: Used PCA (Principal Component Analysis) to reduce dimensionality and visualize clusters in 2D space.
💡 Business InsightsHigh Income, High Spend: Target with premium loyalty programs.
Low Income, High Spend: Target with flash sales and trend-based marketing.
Low Income, Low Spend: Target with essential-value discounts.
⚡ Task 3: Energy Consumption Forecasting🎯
Objective
Forecast short-term household energy usage using historical time-based patterns.
⚙️ Approach
Data Processing: Parsed datetime columns and resampled data to handle temporal patterns.
Feature Engineering: Engineered time-based features such as hour of the day and day of the week.
Modeling: Developed a Random Forest Regressor to predict energy usage.
Evaluation: Measured performance using Mean Absolute Error (MAE).
📈 ResultsThe model successfully captured cyclical daily consumption patterns.
Temporal features (hour of day) were the most significant indicators of load spikes.
🛠️ Tools & LibrariesData Handling: pandas, numpy.Machine Learning: scikit-learn, shap.Visualization: matplotlib, seaborn, plotly.Data Sourcing: ucimlrepo.🚀 Installation & SetupTo run these notebooks locally, clone the repository and install the dependencies:Bash# Clone the repository
git clone https://github.com/maryamadeeba/Data-Science-Analytics-Internship-Phase-II.git

# Install requirements
pip install -r requirements.txt
