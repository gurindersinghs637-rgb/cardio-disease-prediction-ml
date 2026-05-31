Cardiovascular Disease Prediction Using Machine Learning
📌 Project Overview

Cardiovascular diseases are among the leading causes of death worldwide. This project aims to predict the presence of cardiovascular disease using Machine Learning techniques based on patient health and lifestyle information.

The system analyzes medical attributes such as blood pressure, cholesterol level, glucose level, body measurements, and lifestyle habits to determine the likelihood of cardiovascular disease.

🎯 Objectives
Predict cardiovascular disease using machine learning algorithms.
Perform data preprocessing and cleaning.
Conduct exploratory data analysis (EDA).
Engineer new health-related features.
Compare multiple machine learning models.
Select the best-performing model for prediction.
📊 Dataset Information

The dataset contains patient health records with the following attributes:

Gender
Height
Weight
Systolic Blood Pressure (ap_hi)
Diastolic Blood Pressure (ap_lo)
Cholesterol Level
Glucose Level
Smoking Habit
Alcohol Consumption
Physical Activity
Cardiovascular Disease Status (Target Variable)
⚙️ Data Preprocessing

The following preprocessing steps were performed:

Handling invalid and unrealistic values
Removing outliers
Data cleaning
Feature scaling using StandardScaler
Feature engineering
🔧 Feature Engineering

Additional health indicators were created:

Body Mass Index (BMI)

BMI = Weight / Height²

Pulse Pressure

Pulse Pressure = Systolic BP − Diastolic BP

Mean Arterial Pressure (MAP)

MAP = (Systolic BP + 2 × Diastolic BP) / 3

🤖 Machine Learning Models Used
Logistic Regression

Accuracy: 72.66%

Random Forest Classifier

Accuracy: 69.13%

Decision Tree Classifier

Accuracy: 64.00%

🏆 Best Model

Logistic Regression achieved the highest accuracy and was selected as the final prediction model.


How to Open and Run the Project
If the Notebook Does Not Open on GitHub

Sometimes GitHub may display an error while previewing large Jupyter Notebook (.ipynb) files. If this happens:

Click the Download Raw File option from GitHub.
Save the notebook file to your local system.
Open Jupyter Notebook, JupyterLab, or VS Code.
Navigate to the project folder.
Open the downloaded .ipynb file locally.
