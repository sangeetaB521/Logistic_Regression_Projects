# 📊 Logistic Regression

This repository contains machine learning models using **Logistic Regression** for binary and multi-class classification problems. Implemented using Python's `scikit-learn` and `pandas`, these notebooks demonstrate end-to-end pipelines from data preprocessing to evaluation.

---

## 📁 Contents

- [`Advertisement.ipynb`](./Advertisement.ipynb): Predict whether a user clicks on an online advertisement.
- [`Housingrent.ipynb`](./Housingrent.ipynb): Predict housing rent category using logistic regression (classification approach).

---

## 📌 Advertisement Click Prediction

- **Objective**: Predict if a user will click on an ad based on demographic and behavioral features.
- **Features**:
  - Daily time spent on site
  - Age
  - Area income
  - Daily internet usage
  - Gender
- **Target**: Clicked on Ad (Yes/No)
- **Model**: Binary Logistic Regression
- **Steps**:
  - Data cleaning & visualization
  - Feature selection
  - Train-test split
  - Model training and prediction
  - Evaluation using accuracy, confusion matrix, and classification report

---

## 🏘️ Housing Rent Category Prediction

- **Objective**: Classify house rent into predefined ranges or categories.
- **Features**:
  - Area, BHK, Size (sqft), City, Furnishing Status, Tenant Type
- **Target**: Rent category (e.g., Low, Medium, High)
- **Model**: Multi-class Logistic Regression
- **Steps**:
  - Data preprocessing and encoding
  - Train-test split
  - Logistic Regression for multi-class classification
  - Model evaluation using accuracy and confusion matrix

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
