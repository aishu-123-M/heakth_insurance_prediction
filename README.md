# Medical Insurance Cost Prediction

## 📌 Project Overview

This project focuses on predicting **medical insurance charges** based on personal and health-related factors.

The dataset contains information such as age, gender, BMI, number of children, smoking status, region, and insurance charges.

## 🎯 Objective

The main objective is to build a **Machine Learning regression model** that can predict the medical insurance cost for an individual based on the available features.

## 📊 Dataset

The dataset contains **1,338 records** and **7 columns**.

### Features

* `age` – Age of the individual
* `sex` – Gender
* `bmi` – Body Mass Index
* `children` – Number of children
* `smoker` – Smoking status
* `region` – Residential region
* `charges` – Medical insurance cost

The target variable is:

```text
charges
```

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 🤖 Machine Learning

This project uses **Regression** techniques because the target variable, `charges`, is a continuous numerical value.

The categorical features such as `sex`, `smoker`, and `region` are processed before training the model.

The dataset is divided into training and testing data to evaluate the model's performance.

## 📈 Model Evaluation

The model performance can be evaluated using regression metrics such as:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## 📌 Key Learning

Through this project, I learned how to:

* Explore and understand a real-world dataset
* Perform data preprocessing
* Handle categorical variables
* Analyze relationships between features
* Build a regression model
* Split data into training and testing sets
* Evaluate regression model performance
* Predict insurance charges
