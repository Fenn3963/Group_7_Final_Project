# Group 7 – Breast Cancer Detection Using Machine Learning

[🔗 GitHub Repository](https://github.com/Fenn3963/Group_7_Final_Project)  
[🔗 Google Colab Notebook](https://colab.research.google.com/drive/15_pyX_zWnkMVYfMgSdWq5JTvRZd3910H#scrollTo=fOx05XxZ-hYp)

## Overview

This project applies machine learning to classify breast cancer cases using clinical and imaging-based features. The goal is to improve early detection accuracy while preserving model interpretability, supporting clinical decision-making.

We compare classification models and feature selection strategies, balancing performance and explainability.

---

## Objectives

- Build a machine learning pipeline for breast cancer classification.
- Compare multiple classifiers and feature selection techniques.
- Use SHAP for explainable AI to visualize feature importance.

---

## Research Questions

1. Can machine learning models accurately classify breast cancer using clinical and imaging features?
2. How does feature selection improve model performance, interpretability, and computational efficiency?
3. Which features are most predictive of malignancy?

---

## Models Evaluated

- Logistic Regression (baseline)
- Random Forest
- Support Vector Machine (SVM)
- Gradient Boosting
- Multi-Layer Perceptron (MLP)

---

## Dataset

This project uses the dataset from [Breast Cancer Diagnostic dataset on Kaggle](https://www.kaggle.com/datasets/imtkaggleteam/breast-cancer)

- **Target**: Diagnosis — M (Malignant) or B (Benign)
- **Features**:  
  - Radius, Texture, Perimeter, Area  
  - Smoothness, Compactness, Concavity, Concave Points  
  - Symmetry, Fractal Dimension  

This dataset is widely used for binary classification tasks in medical ML research.

---

### Libraries used

pandas — for data manipulation and preprocessing

numpy — for numerical operations and array handling

scipy — used for statistical tests and data science utilities

matplotlib — for plotting graphs and visualizations

seaborn — enhanced statistical data visualization

tabulate — formats summary tables for clean console output

scikit-learn — ML models, preprocessing, metrics, and feature selection

tensorflow — for building and training deep learning models (MLP)

shap — for explainable AI and feature importance visualization
