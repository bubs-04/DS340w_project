# DS340w_project
# Explainable Hybrid Ensemble Framework for Credit Risk Prediction

## Overview
This project develops an explainable machine learning framework for credit risk prediction in auto lending. The goal is to balance predictive accuracy with model interpretability.

Traditional models such as Logistic Regression provide transparency but fail to capture nonlinear relationships. Ensemble models improve performance but are often difficult to interpret. This project combines both using ensemble learning and explainable AI techniques.

---

## Objectives
- Build a credit risk prediction model
- Handle class imbalance using SMOTE
- Compare multiple machine learning models
- Improve performance using a stacking ensemble
- Provide model interpretability using SHAP

---

## Models Used
- Logistic Regression
- Random Forest
- LightGBM
- Hybrid Stacking Ensemble

---

## Methodology

### Data Preprocessing
- Missing value handling
- Categorical encoding
- Feature selection
- Normalization

### Data Split
- 70% Training
- 10% Validation
- 20% Testing

### Class Imbalance
- SMOTE (Synthetic Minority Oversampling Technique)

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- AUC-ROC

---

## Results

| Model               | Accuracy | AUC  | F1 Score |
|--------------------|----------|------|----------|
| Logistic Regression| 0.83     | 0.91 | 0.85     |
| Random Forest      | 0.86     | 0.93 | 0.87     |
| LightGBM           | 0.87     | 0.94 | 0.88     |
| Hybrid Ensemble    | 0.89     | 0.95 | 0.90     |

The hybrid ensemble achieved the best performance across all metrics.

---

## Explainability
- SHAP was used to identify important features
- Local explanations were used to interpret individual predictions

---

## Project Structure
