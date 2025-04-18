Diabetes Prediction using Machine Learning

📌 Introduction

This notebook explores the use of machine learning models to predict diabetes in individuals based on health metrics like glucose levels, BMI, and insulin. Using a dataset (diabetes.csv) of medical diagnostics, the project cleans and analyzes the data before applying classification algorithms.

🔍 Methods

Data Preprocessing:

Addressing missing or skewed values

Visual exploration using Seaborn and Matplotlib

Feature scaling for better model performance

Models Used:

Logistic Regression

Random Forest Classifier

K-Nearest Neighbors (KNN)

Naive Bayes (GaussianNB)

Evaluation Metrics:

Accuracy Score

Confusion Matrix

Classification Report

ROC-AUC Score

📊 Results

All four models were trained and evaluated on the same dataset. Random Forest achieved the highest accuracy, while Logistic Regression and KNN performed reasonably well. Confusion matrices and ROC curves were used to interpret classification performance.



✅ Conclusion

The Random Forest model proved most effective in identifying diabetes cases, showing robustness in handling nonlinear relationships and variable importance. Logistic Regression was also useful for interpretability. Future work can include hyperparameter tuning and model ensembling.

🚀 How to Run

Clone this repo

Ensure diabetes.csv is in your working directory

Run the notebook Diabaetes_Prediction.ipynb

[pip install -r requirements.txt
jupyter notebook Diabaetes_Prediction.ipynb]
