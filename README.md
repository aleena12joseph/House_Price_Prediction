# 🏠 House Price Prediction Using Machine Learning

A machine learning project that predicts house prices using features like area, bedrooms, bathrooms, and furnishing status using the Linear Regression algorithm.

---

## 📌 Problem Statement

To build a predictive system that estimates the price of houses based on historical data and features. This aids buyers and sellers in making informed decisions.

---

## 💡 Proposed Solution

* Use historical housing data with multiple features
* Apply preprocessing and handle categorical data
* Train a Linear Regression model
* Evaluate accuracy using standard metrics
* Visualize prediction vs actual results

---

## 🚰 Technologies Used

* Python
* Google Colab
* pandas, numpy – for data processing
* seaborn, matplotlib – for visualization
* scikit-learn – for machine learning models and evaluation

---

## 📁 Dataset

The dataset (`Housing.csv`) contains attributes:

* `price` (target variable)
* `area`, `bedrooms`, `bathrooms`, `stories`, `parking` (numerical)
* `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus` (categorical)

---

## 🧠 Machine Learning Model

### 🔹 Algorithm: Linear Regression

Linear Regression was chosen for its simplicity, interpretability, and effectiveness in modeling linear relationships between independent variables and the target variable (price).

### 🔸 Input Features:

* Numerical: area, bedrooms, bathrooms, stories, parking
* Categorical: Converted using one-hot encoding

### 🔸 Training Process:

* Train-test split (80/20)
* Linear Regression model trained using training data
* No hyperparameter tuning needed due to model simplicity

### 🔸 Prediction:

* Predict prices on test data
* Compare predictions with actual values

---

## 📊 Model Evaluation

| Metric                   | Value                 |
| ------------------------ | --------------------- |
| Mean Squared Error (MSE) | 1,771,751,116,594.035 |
| Root MSE (RMSE)          | 1,331,071.42          |
| R² Score                 | 0.649                 |

The model explains approximately 65% of the variance in house prices.

---

## 📈 Visualization

To better understand the model's performance, we created a scatter plot comparing the predicted house prices against the actual values. Ideally, if the predictions were perfect, all points would lie along the diagonal line. In our case, the plot shows that most of the points are reasonably close to this line, indicating that the model has learned the underlying pattern in the data to a good extent. Although there are some deviations, the results suggest a fair level of accuracy for a simple regression model.

---

## 🚀 Future Scope

* Use advanced algorithms like Random Forest, XGBoost
* Incorporate location-based data (longitude, latitude)
* Deploy as a web-based app with user input form
* Introduce time-dependent factors and economic indicators

---

## ✅ Summary

This project demonstrates how to apply machine learning (Linear Regression) to predict house prices. The process includes data preprocessing, model training, evaluation, and visualization to ensure a practical and deployable solution.
