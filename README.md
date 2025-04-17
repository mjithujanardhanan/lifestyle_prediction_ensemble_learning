# # 🧬 Lifestyle Disease Prediction using Ensemble Learning

This project focuses on predicting lifestyle-related health conditions based on user input data using various machine learning models, with an emphasis on ensemble techniques to improve performance and accuracy.

## 📌 Overview

- **Goal**: Predict if a person is likely to develop lifestyle-related diseases based on attributes like smoking, alcohol intake, physical activity, BMI, and more.
- **Approach**: Use multiple machine learning models and ensemble techniques to enhance prediction accuracy.
- **Tools**: Python, scikit-learn, pandas, matplotlib, seaborn

## 🧠 Models Used

- **Base Models**:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)

- **Ensemble Techniques**:
  - Voting Classifier (Hard and Soft Voting)
  - Bagging (e.g., Random Forest)
  - Boosting (AdaBoost, Gradient Boosting)

## 📊 Dataset

- The dataset includes features such as:
  - Age, Gender
  - Smoking & Alcohol consumption
  - Exercise habits
  - Body Mass Index (BMI)
  - Sleep time, stress level
  - Diabetes, blood pressure, cholesterol levels

- **Target**: Lifestyle disease classification (binary classification problem)

## 🔍 Exploratory Data Analysis (EDA)

- Performed correlation analysis and visualized feature relationships
- Identified highly influencing features on disease prediction
- Handled missing values and outliers as necessary

## ⚙️ Model Evaluation

- Metrics used:
  - Accuracy
  - Precision, Recall, F1-score
  - ROC-AUC Curve
  - Confusion Matrix

- Ensemble learning (particularly soft voting) improved performance over individual classifiers.

## 🧪 Results

- Best accuracy achieved using ensemble method: **VotingClassifier with SVM, Random Forest, and Logistic Regression**
- Model demonstrated balanced performance across evaluation metrics

