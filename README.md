# 🩺 Predictive Modeling for Diabetes Using NHANES Data

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-orange)
![Healthcare](https://img.shields.io/badge/Domain-Healthcare-green)
![Dataset](https://img.shields.io/badge/Dataset-NHANES-red)
![Status](https://img.shields.io/badge/Project-Completed-success)

## 📌 Project Overview

This project focuses on building a **machine learning–based diabetes prediction system** using real-world clinical data from the **National Health and Nutrition Examination Survey (NHANES)**.  
The objective is to analyze key health indicators and accurately classify individuals as diabetic or non-diabetic using supervised learning techniques.

The project demonstrates an **end-to-end healthcare analytics pipeline**, from raw data preprocessing and exploratory data analysis (EDA) to model comparison, evaluation, and interpretation.

---

## 🧬 Dataset

- **Source:** National Health and Nutrition Examination Survey (NHANES), CDC (USA)
- **Type:** Government-collected clinical and laboratory data
- **Records Used:** ~4,950 participants
- **Key Features:**
  - Age
  - Gender
  - Body Mass Index (BMI)
  - Blood Pressure (Systolic & Diastolic – Mean)
  - Haemoglobin
- **Target Variable:** Diabetes status (Binary Classification)

🔗 Official Dataset: https://www.cdc.gov/nchs/nhanes/

---

## 🔧 Data Preprocessing

- Merged multiple NHANES component files using participant identifiers
- Handled missing laboratory values using **median imputation**
- Aggregated repeated blood pressure readings using mean values
- Removed redundant identifiers and non-informative fields
- Applied feature scaling for model compatibility
- Ensured no data leakage during train–test split

---

## 📊 Exploratory Data Analysis (EDA)

EDA revealed strong clinical relationships:
- Diabetes prevalence increases with **age**
- Higher **BMI** and **blood pressure** are associated with diabetes
- **Haemoglobin** emerged as a highly influential laboratory feature
- Balanced class distribution suitable for classification modeling

Visualizations included:
- Class distribution plots
- Feature-wise boxplots
- Correlation heatmaps
- Scatter plots for clinical trends

---

## 🤖 Models Implemented

The following classification models were trained and evaluated:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Support Vector Machine (SVM)

---

## 📈 Model Evaluation

Models were compared using healthcare-appropriate metrics:

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- ROC-AUC  

✅ **Gradient Boosting** achieved the best overall performance, offering:
- High ROC-AUC (~0.94)
- Strong recall and F1-score
- Robust handling of non-linear feature interactions

Evaluation techniques included:
- Confusion Matrix
- ROC Curve
- Feature Importance & Permutation Importance

---

## 🏆 Key Outcome

> **Gradient Boosting was selected as the final model** due to its superior discriminative ability and balanced performance across all evaluation metrics.

The results align well with established medical knowledge, reinforcing the reliability of the predictive framework.

---

## 🚀 Applications

- Diabetes risk screening
- Clinical decision support systems
- Public health analytics
- Healthcare-focused ML research

---

## 📌 Conclusion

This project highlights the importance of **data understanding, clinical relevance, and robust evaluation** in healthcare machine learning.  
It demonstrates how government health data can be effectively transformed into actionable predictive insights.

---

## 👤 Author

**Abhishek Kashyap**  
Data Science & Machine Learning Enthusiast  

---

⭐ If you find this project useful, consider starring the repository!
