# 📉 Customer Churn Prediction

This project predicts customer churn for a telecommunications company using machine learning. The objective is to build a classification model that identifies customers who are likely to stop using the service.

---

## 🧠 Project Overview

- **Goal**: Predict customer churn using customer data.
- **Techniques Used**: Exploratory Data Analysis (EDA), Feature Engineering, Machine Learning.
- **Model Used**: Random Forest Classifier (chosen for performance and interpretability).
- **Dataset**: 7,043 customer records with features including:
  - Demographics
  - Services subscribed
  - Account details
  - Churn status (target)

---

## 📁 Dataset Information

The dataset includes the following key columns:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `InternetService`, `Contract`
- `MonthlyCharges`, `TotalCharges`
- `Churn` (target variable)

---

## 🧹 Data Preprocessing

- Handled missing values
- Encoded categorical features (Label Encoding / One-Hot Encoding)
- Scaled numerical variables where required
- Dropped unnecessary or duplicate features

---

## 📊 Exploratory Data Analysis (EDA)

Visualizations were used to uncover insights such as:
- Churn rates by contract type
- Relationship between tenure and churn
- Impact of internet and tech support services on churn

---

## ⚙️ Feature Engineering

- Selected important features based on correlation and domain knowledge
- Engineered new features (e.g., number of services subscribed)
- Removed low-impact or redundant columns

---

## 🤖 Model Training

Multiple models were tested:
- Logistic Regression
- Decision Tree
- SVM
- ✅ **Random Forest Classifier** (selected)

---

## 💻 Installation & Usage

### ✅ Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
