# 📊 Logistic Regression

This repository contains machine learning models using **Logistic Regression** for binary and multi-class classification problems. Implemented using Python's `scikit-learn` and `pandas`, these notebooks demonstrate end-to-end pipelines from data preprocessing to evaluation.

---

## 📁 Contents

- [`Advertisement.ipynb`](./Advertisement.ipynb): Predict whether a user clicks on an online advertisement.
- [`Housingrent.ipynb`](./Housingrent.ipynb): Predict housing rent category using logistic regression (classification approach).
- [`MLPRAC.ipynb`](./MLPRAC.ipynb): Binary classification using age and salary.
- [`Thyroid_cancer_risk.ipynb`](./Thyroid_cancer_risk.ipynb): Predict the likelihood of thyroid cancer using patient medical features.

---

## 🧪 Thyroid Cancer Risk Prediction

- **Objective**: Classify whether a patient is at risk of thyroid cancer based on medical features.
- **Model**: Binary Logistic Regression
- **Features**: Includes demographic and diagnostic features such as age, tumor characteristics, etc.
- **Steps**:
  - Data cleaning and preprocessing
  - Train-test split
  - Logistic Regression model training
  - Evaluation using classification report and accuracy
- **Tools**: `LogisticRegression`, `train_test_split`, `classification_report`

---

## ⚙️ Requirements

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
