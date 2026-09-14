# Titanic Survival Prediction

A machine learning project that predicts passenger survival on the Titanic using Logistic Regression.

## 📊 Project Overview
This project uses the classic Titanic dataset to build a binary classification model that predicts whether a passenger survived or not, based on features like passenger class, age, gender, and fare.

## 🛠️ Tech Stack
- Python
- Pandas (data cleaning & manipulation)
- Scikit-learn (model building & evaluation)

## 🔍 Process
1. **Data Cleaning**: Handled missing values (Age filled with mean, Cabin column dropped due to high missing data)
2. **Feature Engineering**: Converted categorical data (Sex) into numerical format
3. **Model Training**: Split data into train/test sets and trained a Logistic Regression model
4. **Evaluation**: Achieved **81% accuracy** on test data

## 📈 Results
The model achieved an accuracy of **81%** in predicting passenger survival.

## 🚀 Future Improvements
- Try other algorithms (Random Forest, SVM) for comparison
- Add more feature engineering (extract titles from names)
- Hyperparameter tuning for better accuracy
