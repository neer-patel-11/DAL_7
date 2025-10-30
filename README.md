Name :- Neer Patel

Roll no :- DA25M021


# 🛰️ Multi-Class Model Selection: ROC & Precision-Recall Analysis

## 📋 Assignment Overview

**Topic:** Multi-Class Classification using ROC and Precision-Recall Curves  
**Dataset:** UCI Landsat Satellite (6-class land cover classification)

This assignment explores model selection for a complex multi-class classification problem using comprehensive evaluation metrics beyond simple accuracy.

---

## 🎯 Objectives

- Train and compare 6 different classifiers (KNN, SVM, Decision Tree, Logistic Regression, Naive Bayes, Dummy Classifier)
- Implement **One-vs-Rest (OvR)** approach for multi-class ROC and PRC analysis
- Generate **macro-averaged ROC curves** and **Precision-Recall curves**
- Compare model performance across different decision thresholds
- Understand trade-offs between ROC-AUC and Precision-Recall metrics
- Identify models with AUC < 0.5 and analyze their behavior

---

## 📊 Key Components

### Part A: Data Preparation & Baseline [5 points]
- Load and standardize Landsat dataset
- Train all 6 models and calculate F1-scores

### Part B: ROC Analysis [20 points]
- Implement multi-class ROC using One-vs-Rest
- Plot macro-averaged ROC curves for all models
- Identify best/worst performers and interpret AUC scores

### Part C: Precision-Recall Analysis [20 points]
- Explain PRC advantages for imbalanced classes
- Plot macro-averaged PRC curves
- Analyze curve behavior and Average Precision (AP)

### Part D: Final Recommendation [5 points]
- Compare rankings across F1, ROC-AUC, and PRC-AP
- Recommend best model with comprehensive justification

---

## 🏆 Results Summary

**Winner:** K-Nearest Neighbors (k=5)
- **F1-Score:** 0.9037 (1st place)
- **ROC-AUC:** 0.9786 (2nd place)
- **PRC-AP:** 0.9217 (1st place)

KNN demonstrates excellent precision-recall balance, consistent performance across thresholds, and robust handling of multi-class classification.

---

## 🚀 Technologies Used

- Python 3.x
- scikit-learn (model training & evaluation)
- NumPy & Pandas (data processing)
- Matplotlib (visualizations)
- Jupyter Notebook (reproducible analysis)

---
