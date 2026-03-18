# 🏀 NCAA Tournament Outcome Prediction (Kaggle)

This project predicts the probability of one team defeating another in the NCAA basketball tournament using machine learning.

## 📌 Problem Statement
Given two teams, predict the probability that Team A will beat Team B.

## 📊 Dataset
- Regular season results
- Tournament results
- Team seeds

## ⚙️ Features
- Seed difference
- Seed ratio
- Win rate difference
- Score difference

## 🤖 Models Used
- Logistic Regression (baseline)
- XGBoost (final model)

## 📈 Results
- Validation Accuracy: ~73%
- Stable generalization (low overfitting)

## 🚀 Key Learnings
- Feature engineering is more important than model complexity
- Seed-based features dominate predictions
- Handling data pipelines is critical in ML

## 📁 Project Structure
  ```
  march-mania-ml/
  ├── notebooks/
  │   └── main.ipynb
  ├── src/
  │   ├── data_processing.py
  │   ├── feature_engineering.py
  │   └── train.py
  ├── submission/
  │   └── submission.csv
  ├── data/
  ├── README.md
  └── requirements.txt
  ```
