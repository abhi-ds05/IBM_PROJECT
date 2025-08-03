# IBM_PROJECT
# PMGSY Scheme Classification using Machine Learning

## 📌 Overview

This project aims to automate the classification of rural road and bridge construction projects under the **Pradhan Mantri Gram Sadak Yojana (PMGSY)** into their respective schemes (e.g., PMGSY-I, PMGSY-II, RCPLWEA). 

Manual classification is time-consuming, error-prone, and difficult to scale across thousands of projects. By using machine learning techniques, we build a robust and scalable classification model based on physical and financial characteristics of the projects.

---

## 🚀 Features

- Automatic classification of projects into PMGSY schemes.
- Supports models like Random Forest, XGBoost, SVM, and Logistic Regression.
- High accuracy and performance (94.2% with XGBoost).
- Preprocessing pipeline: missing values, scaling, encoding.
- Evaluation metrics: Accuracy, Precision, Recall, F1 Score, Confusion Matrix.

---

## 🧠 Machine Learning Models

| Model              | Accuracy |
|-------------------|----------|
| Logistic Regression | 85.4%   |
| Random Forest       | 91.7%   |
| XGBoost             | **94.2%** |
| SVM                 | 89.6%   |

---

## 📊 Dataset

You can access the official PMGSY dataset used for this project from:

🔗 **[PMGSY Dataset on INDIAai – AIKOSH Portal](https://aikosh.indiaai.gov.in/web/datasets/details/pradhan_mantri_gram_sadak_yojna_pmgsy.html)**

---

## 🛠️ Installation & Usage

1. Clone the repository:

```bash
git clone https://github.com/yourusername/pmgsy-scheme-classifier.git
cd pmgsy-scheme-classifier
