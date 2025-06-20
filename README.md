# 🤰 Birth Weight Prediction: Machine Learning with Explainable AI

## 📑 Table of Contents
- [📋 Project Overview](#project-overview)
- [🎯 Key Features](#key-features)
- [⚙️ Tech Stack & Dataset](#tech-stack--dataset)
- [🔄 Methodology & Workflow](#-methodology--workflow)
- [📊 Results & Visualizations](#-results--visualizations)
- [📈 Model Performance](#-model-performance)
- [🔮 Future Roadmap](#-future-roadmap)
- [👨‍💻 Team Members (Amrita School of Computing, Bengaluru)](#-team-members-amrita-school-of-computing-bengaluru)
- [🎓 Mentors](#-mentors)
- [🙏 Acknowledgments](#-acknowledgments)

---

## 📋 Project Overview

This project aims to predict neonatal birth weight using clinical and socioeconomic maternal data. It supports **dual prediction**:  
- **Classification**: Low / Normal / Over-weight
- **Regression**: Exact birth weight in kg

The model pipeline integrates **data preprocessing**, **feature selection**, **SMOTE for balancing**, and **Explainable AI (SHAP & LIME)** to ensure interpretability in healthcare settings.

---

## 🎯 Key Features

- 📊 Classification & regression tasks on maternal/neonatal data
- ⚖️ SMOTE for class imbalance correction
- 🧠 Random Forest, SVM, Gradient Boosting models
- 🧮 Feature selection via PCA, RFE, Random Forest importance
- 🧩 Explainable AI with SHAP & LIME for model interpretability

---

## ⚙️ Tech Stack & Dataset

**Language**: Python  
**Libraries**: pandas, scikit-learn, matplotlib, seaborn, SHAP, LIME  
**Dataset**:  
- Records: 1,800  
- Features: 17 maternal characteristics  
- Targets: `LNH` (categorical), `BWt` (numerical)  

### 📋 Feature Summary

**Clinical Features**:  
`Age`, `Height`, `Initial/Final Weight`, `Blood Pressure`, `Hemoglobin`, `Blood Sugar`, `Term Status`  

**Socioeconomic Features**:  
`SEC`, `Education`, `Income`, `Location`, `Healthcare Access`

---


### 🔄 Methodology & Workflow
![image](https://github.com/user-attachments/assets/1c2f1a06-824a-4929-b813-df7240960e85)
Steps:

Understand & clean the data (nulls, inconsistencies)

Apply label encoding for categoricals

Use SMOTE if class imbalance exists

Visualize data & analyze

Feature selection (RF, PCA, RFE)

Train ML models

Evaluate with accuracy/F1 (classification) and RMSE/R² (regression)

Apply LIME & SHAP for interpretability

Interpret & document results

### 📊 Results & Visualizations
Class distribution before/after SMOTE

Correlation heatmaps

SHAP summary plots

LIME prediction explanation graphs

### 📈 Model Performance

#### 🔢 Classification (After SMOTE)

**Model**: Random Forest  
- **Accuracy**: 96.86%  
- **F1 Score**: 96.86%  

#### 📏 Regression

**Model**: Random Forest Regressor  
- **MAE**: 0.0667  
- **RMSE**: 0.1686  
- **R² Score**: 0.9569  

---

## 🔮 Future Roadmap

- [ ] Real-time prediction dashboard  
- [ ] Integration with electronic medical records (EMR)  
- [ ] Additional risk factor inclusion (genetic/environmental)  
- [ ] Web app for field deployment  

---

## 👨‍💻 Team Members (Amrita School of Computing, Bengaluru)

*B.Tech CSE, Batch of 2022–2026*  
**Amrita School of Computing, Bengaluru**  
**Amrita Vishwa Vidyapeetham, India**

- Mudumala Varnika Narayani  
- Naga Ruthvika Durupudi  
- Nunnaguppala Rohit  

---

## 🎓 Mentors

- **Dr. B. Uma Maheswari**  
  Associate Professor, Amrita School of Computing, Bengaluru  

- **Ms. Amulyashree S**  
  Assistant Professor, Amrita School of Computing, Bengaluru  

---

## 🙏 Acknowledgments

This project was developed as part of the academic curriculum for the **B.Tech CSE Batch of 2022–2026** under the mentorship of  
**Dr. B. Uma Maheswari** and **Ms. Amulyashree S**,  
Amrita School of Computing, Amrita Vishwa Vidyapeetham, Bengaluru Campus.

---

> 📚 Developed as part of the academic curriculum at  
> **Amrita School of Computing, Bengaluru – Amrita Vishwa Vidyapeetham, India**
