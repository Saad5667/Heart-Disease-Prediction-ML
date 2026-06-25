# Heart Disease Prediction — ML Classification

**Internship:** DevelopersHub Corporation — AI/ML Engineering Internship
**Intern Name:** MUHAMMAD SAAD USMAN RAJA
**Batch:** June 2026
**Due Date:** 26th June, 2026

---

## Objective

Build a binary classification model to predict whether a patient is at risk of heart disease based on clinical health measurements.

---

## Dataset Information

- **Dataset:** UCI Heart Disease Dataset
- **Source:** Kaggle
- **Total Patients:** 920
- **Features:** 13 clinical features
- **Target:** Binary — 0 No Disease, 1 Disease

---

## Features Used

- age — Age of patient
- sex — Gender
- cp — Chest pain type
- trestbps — Resting blood pressure
- chol — Serum cholesterol
- thalach — Maximum heart rate
- oldpeak — ST depression
- ca — Major vessels count
- thal — Thalassemia type

---

## Libraries Used

- Python 3.11
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Models Trained

- Logistic Regression — Accuracy 83%, AUC 0.90
- Decision Tree — Accuracy 80%, AUC 0.85
- Random Forest — Accuracy 86%, AUC 0.93 (Best Model)

---

## Visualizations Created

1. Target Class Distribution Bar and Pie Chart
2. Age Distribution by Disease Status
3. Gender and Chest Pain vs Disease
4. Correlation Heatmap
5. Clinical Features Violin Plots
6. Model Comparison Charts
7. Confusion Matrix
8. ROC Curves All Models
9. Feature Importance Chart

---

## Key Findings

- Random Forest achieved best performance 86% accuracy
- Top predictors are cp, thalach, oldpeak, ca, thal
- Older patients show higher heart disease risk
- Asymptomatic chest pain most linked to disease
- Model suitable as preliminary clinical screening tool

---

## How to Run

pip install pandas numpy matplotlib seaborn scikit-learn

jupyter notebook task3_heart_disease_prediction.ipynb

---

## Project Structure

- task3_heart_disease_prediction.ipynb
- heart.csv
- README.md

---

DevelopersHub Corporation — AI/ML Engineering Internship 2026
