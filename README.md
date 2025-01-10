# SVM_CNN
Project on SVM/CNN

# **Support Vector Machine (SVM) Classification Project**

## **Overview**
This project implements **Support Vector Machine (SVM)** classifiers for **classification tasks**. The key objectives of this project are:
- Preprocess the dataset for optimal SVM performance.
- Train and evaluate SVM classifiers using **linear** and **non-linear kernels**.
- Use metrics such as **confusion matrix**, **precision**, **recall**, **F1-score**, and **ROC-AUC** to measure performance.

---

## **Problem Statement**
Given a dataset with multiple features, the task is to:
1. Preprocess the data (handle missing values, feature scaling, etc.).
2. Train SVM classifiers to classify the data into categories.
3. Evaluate the performance using standard metrics and visualizations.

---

## **Key Components**

### **1. Data Preprocessing**
- Handle missing data (if any).
- Perform **feature scaling** (standardization) to improve model accuracy.
- Split the dataset into **training** and **testing** sets.

### **2. SVM Classifiers**
- **Linear SVM:** Best for linearly separable data.
- **Non-linear SVM:** Uses RBF and polynomial kernels for non-linear decision boundaries.

### **3. Model Evaluation**
- **Confusion Matrix:** Shows true positives, true negatives, false positives, and false negatives.
- **Classification Report:** Displays precision, recall, F1-score, and accuracy.
- **ROC-AUC Score:** Measures the trade-off between true positive and false positive rates.

---

## **Environment Setup**
Make sure you have Python installed with the following dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn seaborn

/svm-project
│   README.md                      # Documentation
│   2337862_SVM_.ipynb              # Main Jupyter Notebook
│
├── data/
│   └── dataset.csv                 # Dataset used for classification
├── images/
│   └── svm_decision_boundary.png   # Visualizations of decision boundaries
└── utils/
    └── helper_functions.py         # Optional utility functions (if any)

```
