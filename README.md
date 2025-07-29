# 🚢 Titanic - Machine Learning from Disaster

Predict survival on the Titanic using ML classification algorithms like Logistic Regression, KNN, SVM, and more.

## 📌 Objective

Build a classification model to predict whether a passenger survived or not based on features like gender, age, class, etc.

## 📂 Dataset

This project uses the [Titanic dataset from Kaggle](https://www.kaggle.com/competitions/titanic).

- `train.csv` - Training data with labels (Survived or Not)
- `test.csv` - Test data (without survival info)
- `Submission.csv` - Predictions submitted to Kaggle

## 🛠️ Features Used

- Pclass
- Sex
- Age (filled missing with median)
- SibSp
- Parch
- Fare (filled missing with median)
- Embarked (filled missing with mode and encoded)

## 🧠 Algorithms Applied

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## 🔎 Evaluation

Model performance was measured using accuracy score and compared across models.

## 💡 Results

The best accuracy was obtained using [Logistic Regression], achieving an accuracy of [79%] on the test set.

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/itsSatyapriya/titanic-survival-prediction.git
   cd titanic-survival-prediction

