# PowerPulse-Household-Energy-Usage-Forecast

PowerPulse is a machine learning project focused on predicting household energy consumption using historical electrical usage data. By analyzing patterns in power usage, the model helps households optimize energy consumption and assists utility providers in demand forecasting and smart grid management.The goal of this project is to develop a machine learning model that can predict household energy consumption based on historical data.


## 📌 Project Objectives

- Build regression models to predict **Global Active Power** usage.
- Perform comprehensive **data cleaning**, **feature engineering**, and **visualizations**.
- Generate **daily and rolling average consumption features**.
- Evaluate multiple models using **RMSE**, **MAE**, and **R² Score**.



## 🧠 Skills Gained

- Data Preprocessing and Cleaning
- Feature Engineering (Datetime decomposition, rolling averages)
- Regression Modeling (Linear, Ensemble, Neural Networks)
- Evaluation Metrics: RMSE, MAE, R²
- Visualization using Matplotlib & Seaborn



## 📊 Business Use Cases

- **Household Energy Management**: Optimize usage to reduce bills.
- **Utility Load Forecasting**: Predict daily and hourly power demand.
- **Anomaly Detection**: Identify unusual or unauthorized consumption.
- **Smart Grid Integration**: Real-time energy analytics.
- **Environmental Impact**: Reduce carbon emissions by understanding usage trends.

---

##  Approach

### ✅ Data Understanding
- Load the dataset
- Perform EDA to identify patterns, correlations, and missing values

### 🧹 Data Preprocessing and EDA
- Handle missing entries and invalid characters
- Convert date and time to datetime
- Create new features like `Hour`, `Daily_avg_power`, `Rolling_avg_power`
- Normalize numeric features using MinMaxScaler and StandardScaler

### 🔧 Modeling
- Models Used:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - MLP Regressor (Neural Network)
- Train/Test split with `train_test_split`

### 📈 Evaluation Metrics
- **RMSE** (Root Mean Squared Error)
- **MAE** (Mean Absolute Error)
- **R² Score** (Explained Variance)

### 📈 Visualization
  -Actual vs Predicted Plot
  -Energy Trend Over Time
  -Residual Plot (Optional – Detect Errors)

## 📁 Dataset

- **Source**: https://archive.ics.uci.edu/dataset/222/bank+marketing
- **Name**: Individual Household Electric Power Consumption

---

## 🛠️ Technologies Used

- **Language**: Python
- **Libraries**: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`
- **IDE**: Jupyter Notebook 


