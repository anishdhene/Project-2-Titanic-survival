# Project-2-Titanic-survival

# Titanic Survival Prediction using Machine Learning

## 📌 Project Overview

This project was completed as part of the **Pluto Academy AI & ML Internship Program**. The objective was to build, train, and evaluate multiple machine learning models to predict whether a passenger survived the Titanic disaster.

## 📂 Dataset

* Dataset: Titanic Survival Prediction
* Source: Kaggle
* Link: https://www.kaggle.com/c/titanic

## 🎯 Problem Statement

Predict whether a passenger survived or not based on features such as passenger class, sex, age, fare, number of siblings/spouses, number of parents/children, and embarkation point.

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## 🔍 Data Preprocessing

* Checked dataset information and missing values.
* Filled missing values in the Age column using the median.
* Filled missing values in the Embarked column using the mode.
* Removed Cabin column due to excessive missing values.
* Dropped Name and Ticket columns.
* Encoded categorical variables:

  * Sex: Male → 0, Female → 1
  * Embarked: S → 0, C → 1, Q → 2
* Split the dataset into training and testing sets (80:20).

## ⚙ Feature Engineering

Correlation analysis was performed to identify important features. The following features were used:

* Pclass
* Sex
* Age
* SibSp
* Parch
* Fare
* Embarked

## 🤖 Machine Learning Models

Three classification algorithms were trained:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Random Forest Classifier

## 📊 Model Performance

| Model               | Accuracy | Precision | Recall | F1 Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 79.89%   | 77.14%    | 72.97% | 75.00%   |
| KNN                 | 69.83%   | 67.86%    | 51.35% | 58.46%   |
| Random Forest       | 82.68%   | 81.16%    | 75.68% | 78.32%   |

## 🏆 Best Model

**Random Forest Classifier** achieved the highest performance among all models.

* Accuracy: 82.68%
* Precision: 81.16%
* Recall: 75.68%
* F1 Score: 78.32%

## 📈 Confusion Matrix

A confusion matrix was used to evaluate the Random Forest model and analyze prediction performance.

## ✅ Conclusion

* The Titanic dataset was cleaned and preprocessed successfully.
* Three machine learning models were trained and evaluated.
* Random Forest achieved the best performance.
* The confusion matrix showed that the model predicted survival effectively.
* Therefore, Random Forest is the most suitable model for Titanic survival prediction.

## 📁 Files Included

* Titanic_Survival_Prediction.ipynb
* train.csv
* README.md

## 👨‍💻 Author

**Anish Dhene**

Project completed as part of the **Pluto Academy AI & ML Internship Program**.
