# ❤️ Heart Disease Prediction

This project uses machine learning models to predict the likelihood of heart disease based on patient health indicators. It aims to assist in early diagnosis and risk assessment using clinical parameters.

---

## 📊 Dataset Overview

The dataset includes the following medical attributes:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar > 120 mg/dl (fbs)
- Resting ECG Results (restecg)
- Maximum Heart Rate Achieved (thalach)
- Exercise Induced Angina (exang)
- ST Depression Induced by Exercise (oldpeak)
- Slope of the ST Segment (slope)
- Number of Major Vessels Colored by Fluoroscopy (ca)
- Thalassemia (thal)
- **Target**: 1 (disease), 0 (no disease)

---

## 🛠️ Technologies Used

- Python 🐍
- Jupyter Notebook
- Pandas & NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for modeling and evaluation)

---

## 🔍 Project Workflow

1. **Data Preprocessing**
   - Loaded the dataset
   - Checked for null values
   - Converted categorical features using one-hot encoding

2. **Exploratory Data Analysis**
   - Visualized feature distributions
   - Correlation heatmap
   - Identified relationships between features and target

3. **Modeling**
   - Trained multiple classification models:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest
   - Used train-test split for evaluation

4. **Evaluation Metrics**
   - Accuracy Score
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC-AUC curve

---

## 🏆 Best Model

- **Random Forest Classifier**
- Achieved high accuracy and balanced precision-recall performance

---

## 💡 Key Learnings

- Importance of preprocessing and encoding categorical variables
- Comparison of multiple classifiers helps select the most robust one
- Visual tools (like ROC curves) aid in model evaluation and selection

---

## 🚀 Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/heart-disease-prediction.git
   cd heart-disease-prediction
