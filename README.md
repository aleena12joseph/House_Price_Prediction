# 🏡 Boston Housing Price Prediction – Algorithm Comparison

A machine learning project that predicts **house prices** using multiple algorithms on the **Boston Housing dataset**.  
The project compares **Linear Regression, Random Forest, and XGBoost** to evaluate which algorithm performs best.

---

## 📌 Problem Statement

To build a predictive system that estimates the **median value of homes (MEDV)** in Boston based on socio-economic and structural features.  
The goal is to compare multiple regression algorithms and identify the most effective one.

---

## 💡 Proposed Solution

* Use the **Boston Housing dataset** containing 13 independent features and the target variable `MEDV`.  
* Preprocess the data and split into training/testing sets.  
* Train 3 models:
  - **Linear Regression** – baseline model
  - **Random Forest Regressor** – ensemble model
  - **XGBoost Regressor** – gradient boosting model  
* Evaluate using **RMSE** and **R² score**.  
* Compare performance and visualize results.  

---

## 🚰 Technologies Used

* Python  
* pandas, numpy – data processing  
* seaborn, matplotlib – visualization  
* scikit-learn – regression models & metrics  
* xgboost – gradient boosting  

---

## 📁 Dataset

The dataset (`boston.csv`) includes features like:  

- **CRIM**: Crime rate per capita  
- **ZN**: Proportion of residential land zoned  
- **RM**: Average number of rooms per dwelling  
- **LSTAT**: % lower status of population  
- **PTRATIO**: Pupil-teacher ratio  
- **MEDV**: Median value of owner-occupied homes (target)  

---

## 🧠 Machine Learning Models

### 🔹 Linear Regression
* Simple, interpretable baseline model.  
* Assumes linear relationship between features and price.  

### 🔹 Random Forest Regressor
* Ensemble of decision trees.  
* Handles non-linear patterns well.  
* Reduces variance compared to single decision tree.  

### 🔹 XGBoost Regressor
* Gradient boosting algorithm.  
* Highly accurate and efficient for tabular data.  
* Provides feature importance.  

---

## 📊 Model Evaluation

| Algorithm             | RMSE   | R² Score |
|---------------------- | ------ | -------- |
| Linear Regression     | 4.9   | 0.67     |
| Random Forest         | 2.8   | 0.89     |
| XGBoost Regressor     | 2.55   | 0.91     |

✅ **XGBoost performed the best**, explaining ~91% of the variance in house prices.  
Linear Regression provided a good baseline, while Random Forest also achieved strong results.  

---

## 📈 Visualization

1. **Prediction vs Actual** – Scatter plots for each model to show accuracy.  
2. **Feature Importance** – From Random Forest & XGBoost, showing key features like `RM`, `LSTAT`, `PTRATIO`.  
3. **Comparison Bar Chart** – RMSE/R² comparison across algorithms.  

---

## 🚀 Future Scope

* Apply hyperparameter tuning (GridSearchCV / RandomizedSearchCV).  
* Add more features (e.g., location, economic indicators).  
* Deploy as a **Flask/Django web app** for real-time predictions.  
* Try deep learning models (Neural Networks).  

---

## ✅ Summary

This project compares **three machine learning algorithms** for predicting Boston housing prices.  
While Linear Regression serves as a baseline, **XGBoost provides the most accurate predictions**, proving the effectiveness of gradient boosting for regression tasks.  

---
📜 License: MIT

