![Screenshot 2024-03-03 023438](https://github.com/tulika105/predict_employee_salary/assets/159255355/41560dda-7cf4-437b-b7bf-5e89ab4ba45a)
# predict_employee_salary
This repository contains the codebase for an employee salary prediction project. Using machine learning techniques, it aims to forecast the salaries of employees based on various features such as age, gender, years of experience, education level and  job title. Additionally, it provides tools for data visualization and model evaluation.
# About the project
This is an end-to-end ml project aimed at predicting salaries of employees of various job titles.
# Data Preprocessing and Exploratory Data Analysis(EDA)
The project begins with data collection. We obtained the dataset from kaggle and installed all required libraries for this project. We performed data preprocessing such as checking and removing null and duplicate values. We performed EDA such as heatmap to analyse the correlation between numerical features , count plot for categorical columns and histogram/box plot for numerical columns.
# Model Development and Evaluation
We performed feature engineering such as label encoding to convert categorical columns to numerical columns.Then we performed feature scaling in columns age and years of experience using StandardScaler to scal down the values to a standard form. Next we categorize the dataset into independent and dependent features and splitted the dataset into training(80%) and testing(20%). We created a function for the machine learning model and applied linear regression algorithm and performed all the necessary steps such as training the model on trained data, testing it on unseen data and evaluating the performance of the model using various evaluation metrics. We observed that our model predicts 89.11 % accurately on unseen data.
# Technologies used
-	Python
-	Jupyter Notebook
-	Pandas
-	Matplotlib
-	Seaborn
-	Scikit-learn
# Model Deployment using Streamlit
https://predictemployeesalary-zsiyn79qffgvwbx8mtxbbo.streamlit.app/
