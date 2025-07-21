# Regression & Classification Project (Telco + Used Cars)

This repository contains a full machine learning project that addresses two major tasks:

- 📊 Classification (Telco Churn)
- 📈 Regression (Used Car Price Prediction)

The project is structured into separate folders for each task, with well-organized code, data, and a final report.

---

## 📁 Directory Structure

```
├── Classification/
│ ├── ClassificCode.txt # Python code for Telco churn classification
│ ├── telco_customer.csv # Dataset for classification
│
├── Regression/
│ ├── RegressCode.txt # Python code for car price regression
│ ├── used_cars.csv # Dataset for regression
│
├── Report.pdf # Summary report (PDF)
```

---

## 🔍 1. Classification: Telco Churn

### ✔️ Key Features:
- SMOTE for class imbalance
- Feature engineering with tenure interactions
- Multiple models: Logistic Regression, SVM, Random Forest, XGBoost, LightGBM, etc.
- GridSearchCV for hyperparameter tuning
- Voting & Stacking ensemble
- ROC curve + t-test based model comparison

---

## 📈 2. Regression: Used Car Price Prediction

### ✔️ Key Features:
- Engine parsing (e.g., HP × Liter = Engine Output)
- Outlier removal (IQR)
- Feature selection based on correlation
- Log-transform target (`price`)
- Models: Linear, Lasso, Ridge, RF, GBM, KNN, Bagging
- GridSearchCV for tuning
- Residual analysis

---

## 📊 Evaluation Metrics

- **Classification:** F1-score, AUC, Confusion Matrix, t-tests  
- **Regression:** MSE, RMSE, MAE, R², Residual plots

---
