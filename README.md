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

## Task 3: Customer Churn Prediction

**Objective:** Predict customer churn using supervised machine learning classification models.

**Dataset:** IBM Telco Customer Churn dataset containing 7,043 customer records.

**Data Preprocessing:**
- Converted `TotalCharges` to numeric format and handled missing values.
- Applied One-Hot Encoding to categorical features.
- Used stratified train-test splitting (80:20).
- Applied class weighting to address class imbalance.

**Models Used:**
- Random Forest Classifier
- XGBoost Classifier

**Model Evaluation Results:**

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Random Forest | 78.42% | 62.24% | 47.59% | 0.5394 | 0.8223 |
| XGBoost | 76.08% | 53.36% | 78.61% | 0.6357 | 0.8454 |

**Best ROC-AUC:** XGBoost achieved 0.8454 on the test set.

**Notebook:** `customer_churn_prediction.ipynb`

## Repository Contents
### Task 4: NLP Sentiment Classification

**Objective:** Classify customer reviews as positive or negative using Natural Language Processing (NLP).

**Dataset:** Yelp reviews dataset containing review text and star ratings. Three-star reviews were excluded; 1–2 star reviews were labelled Negative and 4–5 star reviews were labelled Positive.

**Preprocessing and Methods:**
- Text vectorization using TF-IDF
- 80/20 stratified train-test split
- Multinomial Naive Bayes
- Logistic Regression
- Evaluation using Accuracy, Precision, Recall, F1-score, Confusion Matrix, and ROC-AUC
- Custom function to predict sentiment for new reviews

**Results:**

| Metric | Multinomial Naive Bayes | Logistic Regression |
|---|---:|---:|
| Accuracy | 80.80% | 90.11% |
| F1-score | 0.8933 | 0.9375 |
| ROC-AUC | 0.9061 | 0.9545 |

**Best-performing model:** Logistic Regression, with 90.11% accuracy and 0.9545 ROC-AUC.

**Notebook:** `sentiment_classification.ipynb`

- `iris_classification.ipynb` — Iris classification notebook
- `housing_price_prediction.ipynb` — California Housing regression notebook
- `README.md` — Project documentation


