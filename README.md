# Diabetes-Prediction
Diabetes Prediction using Machine Learning to classify whether a patient is diabetic based on medical features

# Overview
This project predicts the likelihood of diabetes in patients using machine learning algorithms. It uses medical attributes such as glucose level, BMI, age, insulin level, and other health indicators to classify whether a person is diabetic or not.

# Objective
To build a predictive model that can accurately identify patients at risk of diabetes based on clinical data.

# Dataset
Source: (Kaggle Custom dataset)

(https://www.kaggle.com/datasets/mdnazmussadat1/diabetes-dataset)

# Technologies Used
Python NumPy Pandas Matplotlib / Seaborn Scikit-learn

# Feature distribution 
The feature distribution plots (generated in cell bVDg0pVyvTUq) show the distribution of each feature, separated by the target class (No Diabetes vs. Diabetes). This helps to visually identify which features have different distributions for each class, indicating their potential importance in predicting diabetes. For instance, features like 'Glucose' and 'BMI' often show a shift towards higher values for the 'Diabetes' class compared to the 'No Diabetes' class, suggesting these are strong indicators.

<img width="1017" height="373" alt="faeture distribution&#39;" src="https://github.com/user-attachments/assets/e01d11f4-a805-4453-a865-0615a4fa6520" />

# Machine Learning Models
This Model Trained and evaluated four classification models for heart disease prediction Logistic Regression: A linear model for binary classification, estimating class probabilities. Support Vector Machine (SVM): A powerful model finding optimal hyperplanes, often using an RBF kernel. Random Forest: An ensemble method using multiple decision trees for robust classification. XGBoost: An optimized gradient boosting framework known for efficiency and performance. Models were evaluated using Accuracy, ROC-AUC, F1 Score, and Cross-Validation Accuracy.

<img width="1017" height="418" alt="comparison" src="https://github.com/user-attachments/assets/68cb48ef-1611-4a7b-bddd-844a79d00f30" />

# Result
The analysis trained four classification models, with Logistic Regression emerging as the best performer based on ROC-AUC, achieving an AUC of 0.9948 and an accuracy of 0.9650.

<img width="1017" height="362" alt="roc curve" src="https://github.com/user-attachments/assets/9e36d04c-0575-4702-8c1c-18d6459216df" />

