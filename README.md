# CodeAlpha_CarPricePrediction
# 🚗 Car Price Prediction using Machine Learning

This project is part of my **CodeAlpha Data Science Internship**, where I built a Linear Regression model to predict car prices based on various attributes like year, present price, fuel type, and more.

---

## 📌 Objective

To develop a machine learning model that can accurately **predict the selling price** of a used car, based on features such as manufacturing year, fuel type, seller type, and kilometers driven.

---

## 📁 Dataset

The dataset was provided as part of the internship task. It includes columns such as:

- `Year` – Manufacturing year of the car  
- `Present_Price` – Current ex-showroom price (in lakhs)  
- `Kms_Driven` – Kilometers driven  
- `Fuel_Type` – Petrol / Diesel / CNG  
- `Seller_Type` – Dealer / Individual  
- `Transmission` – Manual / Automatic  
- `Owner` – Number of previous owners  
- `Selling_Price` – Price at which the car was sold (target variable)

---

## 🧠 ML Approach

I used a **Linear Regression model** from `scikit-learn` for predicting the selling price. The workflow included:

1. 📊 Data exploration & cleaning  
2. 🔍 Feature selection & preprocessing  
3. 🔀 Train-test split  
4. 🏗️ Model training using `LinearRegression()`  
5. 📈 Prediction & evaluation  

---

## 📉 Model Evaluation

The model performance was evaluated using:

- ✅ **Mean Absolute Error (MAE)**
- ✅ **Mean Squared Error (MSE)**
- ✅ **Root Mean Squared Error (RMSE)**
- ✅ **R² Score**

These metrics give insights into how close the predictions are to the actual prices.

---

## 📊 Visualization

Here’s a sample plot comparing **actual vs predicted car prices**:

> _(Include a screenshot or use `plt.savefig()` to save and link it)_

---

## 🛠️ Libraries Used

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`

---

## 📦 Folder Structure

