# 📊 Bank Marketing Term Deposit Prediction

## 🎯 Objective
Predict whether a bank customer will subscribe to a term deposit using machine learning models.

---

## 📂 Dataset
- Source: UCI Machine Learning Repository
- Loaded using `ucimlrepo` (no manual download required)

---

## ⚙️ Approach

### 1. Data Loading
- Dataset fetched using `fetch_ucirepo`

### 2. Data Preprocessing
- Encoded categorical variables using Label Encoding
- Split dataset into training and testing sets

### 3. Exploratory Data Analysis (EDA)
- Target distribution visualization
- Basic statistics and structure analysis

### 4. Model Building
- Logistic Regression
- Random Forest Classifier

### 5. Evaluation Metrics
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)
- ROC Curve

### 6. Explainable AI (XAI)
- SHAP used to interpret predictions
- Feature importance and individual prediction explanations

---

## 📈 Results
- Random Forest performed better than Logistic Regression
- Important features identified using SHAP

---

## 🛠️ Tools & Libraries
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- shap
- ucimlrepo

---

## ✅ Conclusion
The model successfully predicts customer subscription behavior and provides insights using explainable AI techniques.

---

## 🚀 How to Run
```bash
pip install -r requirements.txt 


---

# 🛍️ 2. Customer Segmentation — `README.md`

```markdown
# 🛍️ Customer Segmentation using K-Means

## 🎯 Objective
Segment customers based on spending behavior to design targeted marketing strategies.

---

## 📂 Dataset
- Mall Customers Dataset (Kaggle)
- File: `Mall_Customers.csv`

---

## ⚙️ Approach

### 1. Data Loading
- Loaded dataset using pandas

### 2. Exploratory Data Analysis (EDA)
- Scatter plots of income vs spending
- Pattern identification

### 3. Clustering
- Applied K-Means clustering (k=5)

### 4. Dimensionality Reduction
- PCA used for visualization of clusters

---

## 📊 Results
- Customers grouped into 5 segments:
  - High income, high spending
  - High income, low spending
  - Low income, high spending
  - Low income, low spending
  - Average customers

---

## 💡 Business Insights
- Target high-spending groups with premium offers
- Offer discounts to low-spending segments

---

## 🛠️ Tools & Libraries
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (KMeans, PCA)

---

## 🚀 How to Run
1. Place `Mall_Customers.csv` in project folder
2. Run:
```bash
pip install -r requirements.txt


---

# ⚡ 3. Energy Forecasting — `README.md`

```markdown
# ⚡ Energy Consumption Forecasting

## 🎯 Objective
Forecast household energy consumption using historical time-series data.

---

## 📂 Dataset
- Household Power Consumption Dataset (UCI)
-Mannual download is not required
- Processed file: `energy.csv`

---

## ⚙️ Approach

### 1. Data Preprocessing
- Parsed datetime column
- Extracted time-based features (hour)

### 2. Feature Engineering
- Hour-based patterns used for prediction

### 3. Model Building
- Random Forest Regressor

### 4. Evaluation
- Mean Absolute Error (MAE)
- Visualization of actual vs predicted values

---

## 📈 Results
- Model captures basic consumption patterns
- Time-based features significantly impact predictions

---

## 🛠️ Tools & Libraries
- pandas, numpy
- scikit-learn
- matplotlib

---

## 🚀 How to Run
1. Place `energy.csv` in project folder
2. Install dependencies:
```bash
pip install -r requirements.txt