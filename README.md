# 🏡 Boston Housing Price Prediction using PCA & Linear Regression

This project demonstrates a complete machine learning pipeline for predicting housing prices in Boston using **Linear Regression** enhanced by **Principal Component Analysis (PCA)**. The workflow includes data preprocessing, exploratory data analysis (EDA), multicollinearity handling, dimensionality reduction, and model evaluation using R² and RMSE metrics.

---

## 📌 Project Overview

- **Objective**: Predict the median value of owner-occupied homes (`MEDV`) in Boston suburbs.
- **Dataset**: The classic Boston Housing dataset (originally from UCI Machine Learning Repository).
- **Techniques Used**:
  - Data cleaning & preprocessing
  - Exploratory data analysis (EDA)
  - Multicollinearity detection using VIF
  - Dimensionality reduction with PCA
  - Linear Regression model training & evaluation

---

## 🧰 Technologies & Libraries

- Python 3.x
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (PCA, LinearRegression, KNNImputer, StandardScaler, train_test_split)
- `statsmodels` (for VIF calculation)

---

## 📊 Workflow

### 1. Data Cleaning
- Handle missing values using **KNNImputer**
- Drop irrelevant or highly correlated features (based on VIF analysis)

### 2. Exploratory Data Analysis (EDA)
- Visualize feature distributions
- Identify relationships between features and target variable
- Check for skewness and outliers

### 3. Multicollinearity Detection
- Use **Variance Inflation Factor (VIF)** to detect and mitigate multicollinearity

### 4. Dimensionality Reduction
- Apply **Principal Component Analysis (PCA)**
- Use top principal components that retain the majority of data variance

### 5. Model Training & Evaluation
- Train **Linear Regression** on transformed PCA components
- Evaluate using:
  - **R² Score** (explained variance)
  - **RMSE** (root mean squared error)
- Assess model on both training and test datasets

---

## 📈 Results

| Metric     | Training Set | Test Set |
|------------|--------------|----------|
| R² Score   | 0.84 (example) | 0.79 (example) |
| RMSE       | 3.6 (example)  | 4.2 (example)  |

> 📌 *Note: Replace the above scores with your actual model results.*

---

## 📁 Project Structure
