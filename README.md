# Datheon Machine Learning & Data Science Internship

This repository contains machine learning projects completed as part of the Datheon Machine Learning & Data Science Internship.

## Task 1: Iris Flower Classification

**Objective:** Classify iris flowers into three species using machine learning classification algorithms.

**Dataset:** Iris dataset from Scikit-learn.

**Models Used:**
- Logistic Regression
- Decision Tree Classifier

**Evaluation:** Both models achieved 93.33% accuracy on the test dataset.

**Notebook:** `iris_classification.ipynb`

## Task 2: California Housing Price Prediction

**Objective:** Predict median house values using housing-related features.

**Dataset:** California Housing dataset from Scikit-learn.

**Steps Performed:**
- Data exploration and visualization
- Missing-value and duplicate checks
- Train-test split
- Polynomial interaction feature generation
- Imputation and feature scaling
- Regression model training and evaluation

**Models Used:**
- Ordinary Least Squares (OLS) Linear Regression
- Ridge Regression
- Lasso Regression

**Test Results:**

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| OLS | 0.7033 | 0.4809 | 0.6225 |
| Ridge | 0.7440 | 0.5202 | 0.5776 |
| Lasso | 0.7514 | 0.5329 | 0.5692 |

OLS achieved the best test-set performance among the three evaluated models.

**Notebook:** `housing_price_prediction.ipynb`

## Tools and Libraries

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Repository Contents

- `iris_classification.ipynb` — Iris classification notebook
- `housing_price_prediction.ipynb` — California Housing regression notebook
- `README.md` — Project documentation


