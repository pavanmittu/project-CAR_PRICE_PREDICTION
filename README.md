# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview

This project builds a machine learning model to predict the price of used cars based on various features such as fuel type, kilometers driven, transmission, and ownership history.
The goal is to help estimate car resale values accurately.

---

## 🎯 Objective

* Perform data preprocessing and feature engineering
* Train regression models
* Compare model performance
* Select the best model for prediction

---

## 📂 Dataset Features

* Car_Name
* Year
* Present_Price
* Kms_Driven
* Fuel_Type
* Seller_Type
* Transmission
* Owner

---

## ⚙️ Models Used

Regression Algorithms like
* Linear Regression
* Random Forest Regression  etc....

---

## 📊 Model Performance

| Model             | MAE    | MSE      | RMSE   | R² Score |
| ----------------- | ------ | -------- | ------ | -------- |
| Linear Regression | 177.24 | 44178.27 | 210.18 | 0.9025   |
| Random Forest     | 119.75 | 24588.10 | 156.80 | 0.9393   |

✅ Random Forest performed better with higher accuracy.

---

## 📈 Feature Importance

The Random Forest model identifies important features influencing car price such as:

* Present Price
* Year
* Kms Driven
* Fuel Type

---

## 🛠️ Technologies Used

* Python 
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

---

## 📌 Results

* Random Forest achieved better performance
* R² score improved compared to Linear Regression
* Model can predict car price with good accuracy
