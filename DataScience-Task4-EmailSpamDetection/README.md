# Email Spam Detection using NLP 📧🤖

## 📌 Project Overview

This project focuses on detecting whether a text message is **Spam** or **Ham (legitimate)** using Natural Language Processing (NLP) and Machine Learning.

The project demonstrates how text data can be cleaned, transformed into numerical features using TF-IDF, and classified using machine learning algorithms.

## 🎯 Objectives

- Clean and preprocess text messages
- Explore the distribution of spam and ham messages
- Analyze message length and word count
- Convert text into numerical features using TF-IDF
- Train classification models
- Evaluate model performance using multiple classification metrics
- Compare different machine learning models
- Build a function for predicting new messages

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🔍 Data Preprocessing

The dataset was cleaned by:

- Removing unnecessary columns
- Handling missing values
- Removing duplicate messages
- Converting text to lowercase
- Removing unnecessary characters
- Creating cleaned message features

## 📊 Exploratory Data Analysis

The project includes:

- Spam vs Ham distribution
- Message length analysis
- Word count analysis
- Distribution visualizations

## 🧠 NLP — TF-IDF

**TF-IDF (Term Frequency-Inverse Document Frequency)** was used to convert text messages into numerical feature vectors.

This allows machine learning models to process and learn patterns from the text data.

## 🤖 Machine Learning Models

Two classification models were trained:

### 1. Logistic Regression

Logistic Regression was used as the primary classification model for distinguishing between spam and ham messages.

### 2. Multinomial Naive Bayes

Multinomial Naive Bayes was trained as a second model and compared with Logistic Regression.

## 📈 Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

### Model Performance

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 97.00% | 97.50% | 80.69% | 88.30% |
| Naive Bayes | 95.55% | 100.00% | 68.28% | 81.15% |

Based on the overall performance, **Logistic Regression was selected as the better-performing model** for this project.

## 🔎 Key Insight

Recall is particularly important in spam detection because it measures how many actual spam messages are successfully detected. A low recall means that some spam messages may be incorrectly classified as legitimate messages.

## 🚀 Custom Message Prediction

The trained Logistic Regression model can also classify new, unseen messages as:

- Spam 🚨
- Ham / Normal ✅

## 📂 Project Structure

```text
DataScience-Task4-EmailSpamDetection/
│
├── SpamDetection.ipynb
├── spam.csv
├── README.md
└── requirements.txt