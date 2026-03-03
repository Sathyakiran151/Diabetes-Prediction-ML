# 🩺 Diabetes Prediction using Support Vector Machine (SVM)

## 📌 Project Overview
This Machine Learning project predicts whether a patient is diabetic or non-diabetic based on medical diagnostic measurements.  
The model is built using the Support Vector Machine (SVM) algorithm and trained on the Pima Indians Diabetes Dataset.

The objective of this project is to demonstrate end-to-end ML workflow including data preprocessing, model training, evaluation, and building a predictive system.

---

## 📊 Dataset Information
- Dataset: Pima Indians Diabetes Dataset
- Number of Instances: 768
- Number of Features: 8 medical attributes
- Target Variable: Outcome (0 = Non-Diabetic, 1 = Diabetic)

### Features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

---

## ⚙️ Technologies & Libraries Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (optional for visualization)

---

## 🧠 Machine Learning Workflow

1. Data Loading
2. Data Preprocessing
3. Feature & Target Separation
4. Data Standardization using StandardScaler
5. Train-Test Split
6. Model Training using SVM
7. Model Evaluation (Accuracy Score)
8. Building Predictive System

---

## 🤖 Model Details

Algorithm Used: Support Vector Machine (SVM)  
Kernel: Linear  

SVM was selected because:
- It performs well in high-dimensional spaces
- Effective for classification tasks
- Works well with small-to-medium datasets

---

## 📈 Model Performance

- Training Accuracy: ~78%
- Testing Accuracy: ~76%

The model shows balanced performance without significant overfitting.
