# 📊 Logistic Regression Projects

This repository contains a curated collection of machine learning projects that apply **Logistic Regression** for both binary and multi-class classification tasks. All notebooks use Python and libraries such as `scikit-learn`, `pandas`, `matplotlib`, and `seaborn`.

Each project demonstrates a complete ML workflow: data preprocessing, feature selection, model training, evaluation, and interpretation.

---

## 📁 Notebooks

| Notebook                                            | Description                                              | Task Type              |
|-----------------------------------------------------|----------------------------------------------------------|------------------------|
| [`Advertisement.ipynb`](./Advertisement.ipynb)      | Predict whether a user clicks on an advertisement        | Binary Classification  |
| [`Housingrent.ipynb`](./Housingrent.ipynb)          | Predict housing rent category from property features     | Multi-Class Classification |
| [`MLPRAC.ipynb`](./MLPRAC.ipynb)                    | Predict product purchase based on age and salary         | Binary Classification  |
| [`Thyroid_cancer_risk.ipynb`](./Thyroid_cancer_risk.ipynb) | Predict thyroid cancer risk from patient data      | Binary Classification  |

---

## 📌 Project Summaries

### 🖱️ Advertisement Click Prediction
- **Dataset**: User demographics and behavior
- **Goal**: Predict whether a user will click on an online ad
- **Features**: Age, Daily Internet Usage, Area Income, Gender
- **Model**: Binary Logistic Regression
- **Evaluation**: Accuracy, Confusion Matrix, Classification Report

---

### 🏠 Housing Rent Category Prediction
- **Dataset**: Real estate listings
- **Goal**: Classify houses into rent categories (e.g., low/medium/high)
- **Features**: BHK, Size, City, Furnishing Status, Tenant Type
- **Model**: Multi-Class Logistic Regression
- **Evaluation**: Accuracy, Confusion Matrix

---

### 🛍️ Product Purchase Prediction (`MLPRAC`)
- **Dataset**: Simulated dataset with age and salary
- **Goal**: Predict whether a person will buy a product
- **Features**: Age, Estimated Salary
- **Model**: Binary Logistic Regression
- **Extras**: Data visualization and decision boundary plotting

---

### 🧬 Thyroid Cancer Risk Prediction
- **Dataset**: Medical features from patient records
- **Goal**: Predict whether a patient is at risk of thyroid cancer
- **Features**: Age, TSH levels, tumor markers, etc.
- **Model**: Binary Logistic Regression
- **Evaluation**: Accuracy and Classification Report

---

## ⚙️ Requirements

Install the necessary libraries using:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
