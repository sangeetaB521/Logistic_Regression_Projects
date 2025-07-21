# 📊 Logistic Regression

This repository contains machine learning models using **Logistic Regression** for binary and multi-class classification problems. Implemented using Python's `scikit-learn` and `pandas`, these notebooks demonstrate end-to-end pipelines from data preprocessing to evaluation.

---

## 📁 Contents

- [`Advertisement.ipynb`](./Advertisement.ipynb): Predict whether a user clicks on an online advertisement.
- [`Housingrent.ipynb`](./Housingrent.ipynb): Predict housing rent category using logistic regression (classification approach).
- [`MLPRAC.ipynb`](./MLPRAC.ipynb): Binary classification using age and salary with logistic regression.

---

## 📌 Advertisement Click Prediction

- **Objective**: Predict if a user will click on an ad based on demographic and behavioral features.
- **Model**: Binary Logistic Regression
- **Features**: Age, Daily Time on Site, Area Income, Internet Usage, Gender
- **Evaluation**: Accuracy, Confusion Matrix, Classification Report

---

## 🏘️ Housing Rent Category Prediction

- **Objective**: Predict rent category (low, medium, high) based on property features.
- **Model**: Multi-class Logistic Regression
- **Features**: Area, BHK, Size, City, Furnishing Status, Tenant Type
- **Evaluation**: Accuracy, Confusion Matrix

---

## 🧪 Logistic Regression Practice (MLPRAC)

- **Objective**: Classify whether a person buys a product based on age and salary.
- **Model**: Binary Logistic Regression
- **Steps**:
  - Data visualization
  - Standardization
  - Model training
  - Evaluation with confusion matrix
- **Tools**: `StandardScaler`, `train_test_split`, `LogisticRegression`

---

## ⚙️ Requirements

Install dependencies with:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
