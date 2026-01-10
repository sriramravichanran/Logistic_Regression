# ❤️ Heart Disease Prediction using Logistic Regression

## 📌 Project Overview
Heart disease is one of the leading causes of death worldwide.  
This project aims to predict whether a person has heart disease or not using Logistic Regression based on health-related features.

The project demonstrates an end-to-end machine learning workflow, including data analysis, model building, and evaluation using appropriate performance metrics.

---

## 🎯 Problem Statement
To build a machine learning model that can predict the presence of heart disease using patient health data and evaluate its performance using multiple classification metrics.

---

## 🧠 Why Logistic Regression?
- The target variable is binary:
  - 1 → Heart Disease
  - 0 → No Heart Disease
- Logistic Regression is well-suited for binary classification
- It provides probability-based and interpretable results
- Widely used in real-world healthcare risk prediction systems

---

## 🗂 Dataset Description
The dataset contains health-related attributes such as:
- Age
- Gender
- BMI
- Smoking status
- Physical activity
- Other medical indicators

These features are commonly used in real-world clinical risk assessment.

---

## 🔍 Exploratory Data Analysis (EDA)
- Analyzed feature distributions
- Studied relationships between features and heart disease
- Visualized patterns using graphs and plots
- Identified important factors influencing heart disease

EDA helped in understanding data behavior before model building.

---

## ⚙️ Model Building
- Algorithm Used: Logistic Regression
- Split the dataset into training and testing sets
- Trained the model on training data
- Predicted outcomes on test data

---

## 📊 Model Evaluation

### 🔹 Confusion Matrix
The confusion matrix compares actual vs predicted values and helps identify:
- True Positives (TP)
- True Negatives (TN)
- False Positives (FP)
- False Negatives (FN)

This is crucial in healthcare, as missing a real patient (FN) is more dangerous than a false alarm.

---

### 🔹 Performance Metrics Used

| Metric | Purpose |
|------|--------|
| Accuracy | Overall correctness of predictions |
| Precision | Reliability of positive predictions |
| Recall | Ability to detect actual heart disease patients |
| F1 Score | Balance between precision and recall |

### 🔹 Results (Approximate)
- Accuracy: ~91%
- Precision: ~99%
- Recall: ~98%
- F1 Score: ~97%

These results indicate strong model performance, especially in detecting real heart disease cases.

---

## 🏥 Real-World Relevance
This project reflects how real-time healthcare systems work:
- Hospitals use similar models for risk prediction
- Health apps assess patient risk scores
- Insurance companies perform health risk analysis

Logistic Regression is commonly used due to its interpretability and reliability.

---

## 🛠 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 Future Improvements
- Handle class imbalance using SMOTE or class weighting
- Compare with advanced models like Random Forest or XGBoost
- Improve ROC-AUC score
- Perform hyperparameter tuning
- Validate on real-world noisy data

---

## ✅ Conclusion
This project demonstrates how Logistic Regression can be effectively used for heart disease prediction, emphasizing not just accuracy but also critical metrics like recall and precision, which are essential in medical applications.

---

## 📌 Author
Sriram Ravichandran  </n>
