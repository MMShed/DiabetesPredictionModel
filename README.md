# 🩺 Diabetes Prediction – Machine Learning Model Comparison

This project explores and compares multiple supervised machine‑learning algorithms for predicting diabetes using the a kaggle diabetes dataset.  
The entire workflow — from preprocessing to model training, evaluation, and visualization — is implemented in a single Jupyter Notebook for clarity and reproducibility.



## 🔍 Project Motivation

I completed this project **independently** as part of my own research to better understand how different machine‑learning models perform in early‑stage diabetes prediction.  
This analysis was created **to support and complement the team's work** on a *prediabetic monitoring device* by providing data‑driven insight into algorithm selection.



## 📘 Notebook Contents

The Jupyter Notebook walks through the full ML pipeline:

### ✅ 1. Data Preparation  
- Loading and inspecting the dataset  
- Separating features and target labels  
- Train/test split  
- Scaling numerical features using `StandardScaler`

### ✅ 2. Models Implemented  
Five classification models were trained and compared:

- Logistic Regression  
- Random Forest Classifier  
- K‑Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Gradient Boosting Classifier  

### ✅ 3. Evaluation Metrics  
Each model was evaluated using:

- **Accuracy** – overall correctness  
- **Precision** – how often predicted diabetics were actually diabetic  
- **Recall** – ability to detect diabetic patients  
- **F1 Score** – harmonic mean of precision and recall, ideal for medical prediction  

### ✅ 4. Visualization  
A Matplotlib bar chart compares all models across the four evaluation metrics to highlight strengths and weaknesses.



