# 💊 Medicine Recommendation System using Machine Learning

This project aims to build a **Machine Learning-based Medicine Recommendation System** that suggests appropriate medicines based on patient symptoms, disease types, and other health parameters. It leverages classification algorithms to enhance prescription accuracy and support healthcare decision-making.

---

## 📌 Project Objectives

- Recommend suitable medicines based on symptoms or diagnosed diseases.
- Improve efficiency in healthcare support systems.
- Reduce human error in prescribing common medications.
- Build a model that can be easily integrated into medical platforms.

---

## 📂 Dataset

- Source: ['Kaggle'] 
- Features: Symptoms, Disease, Age, Gender, Medical History
- Target: Recommended Medicine(s)

---

## 🛠️ Technologies & Tools

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter/Google Colab

---

## 🧠 ML Algorithms Used

- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Logistic Regression

Model performance is evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

---

## 🧪 How It Works

1. **Data Preprocessing**:
   - Handle missing values
   - Encode categorical features
   - Normalize numerical features

2. **Training & Testing**:
   - Split dataset (Train/Test)
   - Fit models and tune hyperparameters

3. **Prediction**:
   - Input patient details
   - Output recommended medicine(s)

---

## 📊 Sample Output

```bash
Input:
Symptoms: Fever, Headache, Body Pain  
Predicted Disease: Viral Infection  
Recommended Medicine: Paracetamol, ORS, Rest

