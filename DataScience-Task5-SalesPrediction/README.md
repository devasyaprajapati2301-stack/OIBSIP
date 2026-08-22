# Advertising Sales Prediction 📊

## 📌 Project Overview

This project focuses on predicting product sales based on advertising expenditure across different media channels.

The dataset contains advertising spending on:

- TV
- Radio
- Newspaper

The target variable is:

- Sales

The project demonstrates the complete Machine Learning workflow, from data exploration and visualization to model training and evaluation.

## 🎯 Objectives

- Explore and understand the advertising dataset
- Analyze relationships between advertising channels and sales
- Visualize the data using different plots
- Build regression models to predict sales
- Compare Linear Regression and Random Forest Regressor
- Evaluate models using MAE, RMSE, and R² Score

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Exploratory Data Analysis

The project includes:

- Dataset inspection
- Null value analysis
- Statistical analysis
- Pair plots
- Scatter plots
- Correlation heatmap
- Advertising expenditure vs. sales analysis

## 🤖 Machine Learning Models

Two regression models were trained:

### 1. Linear Regression

A baseline regression model used to understand the linear relationship between advertising expenditure and sales.

### 2. Random Forest Regressor

An ensemble learning model consisting of multiple decision trees.

## 📈 Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The models were then compared to identify the better-performing approach for this dataset.

## 📊 Key Insight

TV advertising showed the strongest correlation with Sales compared with Radio and Newspaper advertising.

The machine learning models achieved strong predictive performance, with both models achieving an R² score of approximately 0.95 on the test data.

## 📂 Project Structure

```text
Advertising-Sales-Prediction/
│
├── Advertising.csv
├── Advertising_Sales_Prediction.ipynb
├── README.md
└── requirements.txt