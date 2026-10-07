# 🔍 Interpretable Machine Learning with SHAP & LIME

## 📌 Project Overview

This project focuses on **Interpretable Machine Learning (IML)** using the **Telco Customer Churn** dataset.

The main goal is not only to predict which customers are likely to churn, but also to understand **why the model makes a particular prediction**.

The project explores several approaches to machine learning interpretability, including:

- Glass Box vs Black Box models
- Logistic Regression coefficients
- Gradient Boosting
- Random Forest feature importance
- Permutation Importance
- Partial Dependence Plot (PDP)
- Individual Conditional Expectation (ICE)
- LIME
- SHAP
- SHAP Force Plot
- SHAP Waterfall Plot
- SHAP Summary / Beeswarm Plot
- SHAP Dependence Plot
- Business-oriented model explanations

The project also compares **LIME and SHAP** in terms of explanation consistency, computational speed, and local vs global interpretability.

---

## 🎯 Objectives

The main objectives of this project are:

1. Understand the difference between **Glass Box** and **Black Box** machine learning models.
2. Compare model performance and interpretability.
3. Identify the most influential features for customer churn.
4. Understand how individual features affect model predictions.
5. Use **Permutation Importance** for global feature importance.
6. Use **PDP and ICE** to understand feature effects.
7. Explain individual customer predictions using **LIME**.
8. Explain individual and global model behavior using **SHAP**.
9. Compare LIME and SHAP explanations.
10. Translate technical model explanations into insights for non-technical stakeholders.
11. Understand why model explanations should not automatically be interpreted as causal relationships.

---

# 📊 Dataset

The project uses the **Telco Customer Churn** dataset.

The dataset contains customer information from a telecommunications company and a target variable indicating whether each customer churned.

### Dataset Size

- **7,043 customers**
- **21 original columns**
- **26.5% churn rate**
- **74.5% non-churn**

### Target Variable

`Churn`

| Value | Meaning |
|---|---|
| `Yes` | Customer churned |
| `No` | Customer remained |

The target was converted into binary values:

```text
Yes → 1
No  → 0
