# Heart Disease Prediction using Logistic Regression

This project focuses on the **prediction of heart disease** using logistic regression. It involves preprocessing of a heart disease dataset, binary classification using logistic regression, and evaluation through confusion matrix, classification report, and ROC-AUC curve.

## Project Objective

The main objective of this project is to explore whether a specific feature — **left ventricular hypertrophy** — is significantly associated with heart disease and whether it can be used to build a reliable classifier.

We also aimed to **increase the classification accuracy** of the model. Through careful feature selection and preprocessing, we achieved an approximate **3% improvement in accuracy** over the baseline model.

---
## Methodology

1. **Preprocessing:**
   - Handled categorical features using one-hot encoding.
   - Removed irrelevant columns post-encoding.
   - Selected a specific feature (`left ventricular hypertrophy`) for targeted modeling.

2. **Modeling:**
   - Performed train-test split with 70-30 ratio.
   - Applied `LogisticRegression` from `sklearn` and `Logit` from `statsmodels` for analysis.
   - Printed model coefficients and intercepts.

3. **Evaluation:**
   - Computed `accuracy`, `confusion matrix`, and `classification report`.
   - Generated and plotted the ROC curve.
   - Calculated AUC (Area Under the Curve) to assess model performance.

---

## Results

- Logistic Regression achieved reliable classification on the test data.
- ROC-AUC curve demonstrated good discriminative ability of the model.
- The accuracy improved by approximately **3%** after preprocessing and feature adjustments.

---

## 📊 Visualization

The ROC curve was plotted to illustrate the trade-off between sensitivity and specificity. A higher AUC indicates better model performance.

---

##  Requirements

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `statsmodels`
