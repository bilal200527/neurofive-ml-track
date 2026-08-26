# Task 04 — House Price Prediction Using Linear Regression

## 📌 Overview

This project focuses on **Regression**, a supervised machine learning technique used to predict continuous numerical values.

For this task, I built a **Linear Regression model** to predict house prices using the California Housing dataset available through `scikit-learn`.

## 🎯 Objectives

The main objectives of this task were to:

* Understand the difference between classification and regression
* Select relevant features for predicting house prices
* Train a Linear Regression model using Scikit-learn
* Evaluate the model using RMSE and R²
* Visualize predicted vs. actual house prices
* Interpret the model's performance in simple terms

## 📊 Dataset

**Dataset:** California Housing Dataset

The dataset contains information about California districts and their corresponding median house values.

The target variable used in this project is:

* `MedHouseVal` — Median house value

## 🔑 Selected Features

I selected the following four features:

| Feature    | Description             |
| ---------- | ----------------------- |
| `MedInc`   | Median income           |
| `HouseAge` | Median house age        |
| `AveRooms` | Average number of rooms |
| `AveOccup` | Average occupancy       |

These features were selected because they can have a meaningful relationship with housing prices.

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## 🧠 Machine Learning Model

I used **Linear Regression** from Scikit-learn.

The dataset was divided into:

* **80% Training Data**
* **20% Testing Data**

The model was trained on the training data and evaluated using the unseen testing data.

## 📈 Evaluation Metrics

The model was evaluated using:

### RMSE — Root Mean Squared Error

RMSE measures how far the model's predictions are from the actual house prices. A lower RMSE indicates better prediction accuracy.

### R² Score

R² measures how much of the variation in house prices can be explained by the features used by the model.

My model achieved an R² score of approximately **0.55**.

This means that the selected features explain approximately **55% of the variation in house prices**, while the remaining variation is influenced by other factors that were not included in the model.

> The exact RMSE and R² values may vary slightly depending on the dataset version and execution environment.

## 📉 Visualization

A **Predicted vs. Actual House Prices** scatter plot was created to visually evaluate the model.

The closer the predictions are to the diagonal reference line, the better the model's predictions are.

## 📁 Project Files

```text
Task-04-Regression/
│
├── House_Price_Regression.ipynb
├── README.md
└── results.png
```

## 🚀 Key Learning

Through this task, I learned how regression differs from classification and how Linear Regression can be used to predict continuous values. I also learned how RMSE and R² provide different perspectives on model performance and how visualization can help identify prediction errors.

## 👨‍💻 Author

**Muhammad Bilal Hafeez**

Machine Learning Track — Neurofive Solutions
