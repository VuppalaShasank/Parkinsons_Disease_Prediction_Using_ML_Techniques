# Parkinson’s Telemonitoring – Multi-Model Classification

This repository contains a **machine learning pipeline** for classifying Parkinson’s disease severity from telemonitoring data.  
The project compares multiple algorithms — **Support Vector Machine (SVM)**, **Random Forest**, and **XGBoost** — with **SMOTE** for class balancing, feature scaling, and hyperparameter tuning.

---

## 📌 Features
- **Data Preprocessing**:
  - Missing value handling
  - Label encoding for categorical features
  - Standard scaling for numerical features
- **Target Engineering**:
  - Binary classification target derived from median `motor_UPDRS`
- **Class Imbalance Handling**:
  - SMOTE (Synthetic Minority Oversampling Technique)
- **Multiple ML Models**:
  - Support Vector Machine (SVM)
  - Random Forest Classifier
  - XGBoost Classifier
- **Model Evaluation**:
  - Accuracy, Precision, Recall, F1-score
  - ROC-AUC
  - Confusion Matrix
  - Comparative performance analysis

---

## 📂 Dataset
This project uses the **UCI Parkinson's Telemonitoring Dataset**.  
📄 [Dataset Link](https://archive.ics.uci.edu/ml/datasets/parkinsons+telemonitoring)  

**Key Features Used**:
- **Demographic**: `age`, `sex`, `test_time`
- **Acoustic**: Jitter, Shimmer, NHR, HNR, RPDE, DFA, PPE, and more.

---

## 🛠 Installation

```bash
# Clone the repository
git clone https://github.com/<your-username>/parkinsons-telemonitoring.git
cd parkinsons-telemonitoring

# Install dependencies
pip install -r requirements.txt
