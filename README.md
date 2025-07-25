# Parkinsons-Disease-prediction
# 🧠 Parkinson's Disease Prediction Using Machine Learning

This project uses machine learning to predict whether a person has Parkinson’s disease based on vocal measurements. The model was trained in **Google Colab** and tested locally using **Spyder IDE via Anaconda Navigator**.

---

## 📁 Project Overview

- Developed a binary classification model using **Support Vector Machine (SVM)**.
- Used vocal features (MDVP metrics, jitter, shimmer, etc.) to distinguish between healthy and affected individuals.
- Performed data preprocessing, feature scaling, and accuracy evaluation.
- Built a predictive system for real-time user input and result display.

---

## 📊 Dataset Info

- **Source**: UCI Parkinson's Disease Dataset
- **Features**: 22 voice frequency & amplitude-related attributes such as:
  - `MDVP:Fo(Hz)`, `MDVP:Jitter(%)`, `Shimmer(dB)`, `HNR`, `RPDE`, `DFA`, `spread1`, etc.
- **Target**:
  - `0` – Healthy  
  - `1` – Has Parkinson’s Disease

---

## 🛠️ Tools & Technologies

- **Language**: Python  
- **IDE/Platform**:  
  - [x] **Google Colab** – model development and training  
  - [x] **Spyder (Anaconda Navigator)** – testing and integration  
- **Libraries**:
  - Pandas
  - NumPy
  - Scikit-learn (SVM, StandardScaler, train_test_split, accuracy_score)

---

## 🧪 Workflow Summary

1. Loaded dataset and explored its structure.
2. Checked for missing values and confirmed data types.
3. Scaled features using `StandardScaler`.
4. Split data into training and testing sets.
5. Trained a **Support Vector Machine** classifier.
6. Evaluated performance on both datasets.
7. Built a real-time input prediction system.

---

## 🎯 Accuracy

- **Training Accuracy**: ~86.2%  
- **Testing Accuracy**: ~87.1%

---

## ▶️ How to Run the Project

1. **Clone or download the repository**.
2. **Install dependencies**:
   ```bash
   pip install numpy pandas scikit-learn
