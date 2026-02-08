# Diabetes Predictor 🌟

## Overview
This project predicts diabetes using two powerful machine learning techniques: **Support Vector Machine (SVM)** and **Random Forest (RF)**.  
It is designed to be professional, fully reproducible, and includes:

- Data visualization for insights
- Feature importance analysis for both models
- Model comparison (accuracy, confusion matrix, ROC-AUC)
- Prediction probability for custom inputs
- Interactive workflow in a single **Google Colab Notebook**

The combination of these two models allows for a robust comparison and ensures more reliable predictions.

---

## Dataset
**Pima Indians Diabetes Dataset**  
- **Rows × Columns:** 768 × 9  
- **Features:**
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target:** `Outcome`  
  - `0` → Non-Diabetic  
  - `1` → Diabetic

---

## Techniques Used

### 1. Support Vector Machine (SVM)
- **Linear kernel** SVM was chosen for its simplicity and ability to find the optimal hyperplane separating diabetic and non-diabetic cases.  
- SVM is effective for **high-dimensional data** and provides **feature coefficients**, which can be interpreted as feature importance.  
- It gives probabilistic predictions when `probability=True` is enabled, allowing better understanding of uncertainty.

### 2. Random Forest (RF)
- Random Forest is an **ensemble learning technique** that builds multiple decision trees and aggregates their results.  
- It is highly **robust to overfitting**, handles non-linear relationships, and provides **feature importance scores**.  
- RF is particularly useful for datasets where features have complex interactions.

### Why Both?
- Using both SVM and RF allows **comparison of model performance**:
  - SVM excels in **linear separable data** and provides interpretable coefficients.
  - RF handles **non-linearities and feature interactions** better and often gives higher accuracy on complex datasets.  
- By training both models, we can **choose the most reliable model** for real-world predictions and highlight differences in feature importance.

---

## Project Structure

