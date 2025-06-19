# Diabetes_Prediction



📘 Problem Statement
Predicting the likelihood of diabetes in individuals using clinical and biometric attributes, and identifying which features contribute most to the prediction?



🧠 Skills Applied
Data Cleaning & Imputation

Exploratory Data Analysis (EDA)

Statistical Testing (t-test)

Feature Engineering (np.where, pd.cut, age_group)

Predictive Modeling (Logistic Regression)

Performance Evaluation (accuracy, confusion matrix)

Time Series Simulation + Analysis



🗃️ Dataset Summary
Source: PIMA Indian Diabetes Dataset

Records: 768 patients

Target Variable: diabetes (0 = No, 1 = Yes)

Key Features: glucose_conc, bmi, age, insulin, etc.



📊 Highlights

⚖️ Replaced medically impossible zeroes with column medians

🔍 Strongest predictors: glucose_conc, age, bmi, num_preg

📈 Model accuracy: ~71% with Logistic Regression

📅 Simulated checkup trends using time series

🧪 T-test showed significant difference in glucose_conc by outcome group



🚀 How to Run

bash

pip install -r requirements.txt  # if needed

jupyter notebook diabetes_prediction.ipynb
