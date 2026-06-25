---

### 🔴 Task 3 — Heart-Disease-Prediction-ML

```markdown
# ❤️ Heart Disease Prediction — ML Classification



![Python](https://img.shields.io/badge/Python-3.11-blue)




![Scikit--learn](https://img.shields.io/badge/Scikit--learn-1.3-orange)




![Status](https://img.shields.io/badge/Status-Completed-brightgreen)




![Accuracy](https://img.shields.io/badge/Accuracy-86%25-success)



**Internship:** DevelopersHub Corporation — AI/ML Engineering Internship  
**Intern Name:** Saad  
**Batch:** June 2026  
**Due Date:** 26th June, 2026  

---

## 🎯 Objective

Build a binary classification model to predict whether a patient is at risk of heart disease based on clinical health measurements. This project demonstrates end-to-end ML pipeline from data cleaning to model evaluation.

---

## 📋 Dataset Information

| Property | Detail |
|----------|--------|
| Dataset | UCI Heart Disease Dataset |
| Source | Kaggle |
| Total Patients | 920 |
| Features | 13 clinical features |
| Target | Binary (0=No Disease, 1=Disease) |
| Missing Values | Handled with median imputation |

---

## 📊 Features Used

| Feature | Description |
|---------|-------------|
| age | Age of patient |
| sex | Gender |
| cp | Chest pain type |
| trestbps | Resting blood pressure |
| chol | Serum cholesterol |
| thalach | Maximum heart rate |
| oldpeak | ST depression |
| ca | Major vessels count |
| thal | Thalassemia type |

---

## 🛠️ Libraries Used

| Library | Purpose |
|---------|---------|
| Python 3.11 | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Visualizations |
| Scikit-learn | ML models & evaluation |

---

## 🤖 Models Trained

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | ~83% | ~0.90 |
| Decision Tree | ~80% | ~0.85 |
| **Random Forest** ⭐ | **~86%** | **~0.93** |

---

## 📊 Visualizations Created

| # | Visualization |
|---|--------------|
| 1 | Target Class Distribution (Bar + Pie) |
| 2 | Age Distribution by Disease Status |
| 3 | Gender & Chest Pain vs Disease |
| 4 | Correlation Heatmap |
| 5 | Clinical Features Violin Plots |
| 6 | Model Comparison Charts |
| 7 | Confusion Matrix |
| 8 | ROC Curves — All Models |
| 9 | Feature Importance Chart |

---

## 🔍 Key Findings

- ✅ **Random Forest** achieved best performance — 86% accuracy, 0.93 AUC
- ✅ **Top predictors:** cp, thalach, oldpeak, ca, thal
- ✅ **Older patients** show higher heart disease risk
- ✅ **Asymptomatic chest pain** most linked to disease
- ✅ Model suitable as **preliminary clinical screening tool**
- ⚠️ **False Negatives** minimized — missed disease cases most critical

---

## 📁 Project Structure
