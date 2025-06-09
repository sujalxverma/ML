# Breast Cancer Classification using Logistic Regression

This project builds a logistic regression model to classify breast cancer tumors as **malignant** or **benign** using the **UCI Breast Cancer Wisconsin dataset**. The model includes data preprocessing, hyperparameter tuning, and evaluation using multiple metrics.

---

## 📁 Project Structure
.
├── data.csv # Breast cancer dataset
├── Cancer_Logistic_Regression.py
├── Cancer_Logistic_Regression.ipynb # Google Colab notebook with code
├── model.pkl # Saved model
└── README.md # This file


---

## 📚 Dataset

- **Source:** [Kaggle - Breast Cancer Wisconsin Dataset](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Features:** 30 numeric features describing characteristics of cell nuclei in breast cancer biopsies.
- **Target:** `diagnosis` — M = Malignant, B = Benign

---

## 🚀 Features

- Logistic regression with regularization
- Hyperparameter tuning (`C`) using 10-fold cross-validation
- StandardScaler for feature normalization
- Evaluation with precision, recall, F1-score, and confusion matrix
- 98%+ accuracy on test data

---

## ⚙️ Installation

### 1. Clone the repository:

```bash
git clone https://github.com/sujalxverma/ML.git
cd Projects/Cancer_Logistic_Regression


