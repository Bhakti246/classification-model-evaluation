# 🧠 Classification Models & Evaluation Metrics

## 📌 Project Overview
This project demonstrates a complete machine learning pipeline for **binary classification** using the Breast Cancer dataset.

The goal is to build, evaluate, and compare classification models using industry-standard evaluation metrics.

---

## 🚀 Objectives
- Understand classification vs regression
- Implement Logistic Regression model
- Evaluate model using confusion matrix and metrics
- Plot ROC curve and calculate AUC score
- Handle imbalanced data
- Compare models (Logistic Regression vs Decision Tree)

---

## 📊 Dataset
- **Breast Cancer Dataset** (from scikit-learn)
- Features: 30 numerical features
- Target:
  - `0` → Malignant (Cancerous)
  - `1` → Benign (Non-cancerous)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab / Jupyter Notebook

---

## 🔍 Machine Learning Models
### 1. Logistic Regression
- Used for binary classification
- Outputs probability between 0 and 1
- Simple and efficient model

### 2. Decision Tree Classifier
- Tree-based model
- Easy to interpret
- Can overfit if not controlled

---

## 📈 Evaluation Metrics

### 🔹 Confusion Matrix
- True Positive (TP)
- True Negative (TN)
- False Positive (FP)
- False Negative (FN)

### 🔹 Classification Metrics
- **Precision** → Accuracy of positive predictions  
- **Recall** → Ability to find all positive cases  
- **F1-score** → Balance between precision and recall  

### 🔹 ROC Curve & AUC
- ROC Curve shows model performance
- AUC Score indicates model quality
  - Closer to 1 = Better model

---

## ⚖️ Handling Imbalanced Data
- Used `class_weight="balanced"` in Logistic Regression
- Helps improve performance on minority class

---

## 📊 Results
- Logistic Regression achieved high accuracy (~95%+)
- AUC Score close to 1.0
- Decision Tree showed slightly different performance
- Balanced model improved recall
