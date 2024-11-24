# Diabetes-Prediction-Using-Classification-Method
This project involves building a Diabetes Prediction Model that uses machine learning classification techniques to predict the likelihood of diabetes based on patient data.

# Project Overview
This project aims to predict whether a person has diabetes based on various medical parameters using machine learning classification techniques. The dataset contains medical details such as age, BMI, glucose level, insulin, and others, which are used to train a model that can accurately predict the presence of diabetes.

# Table of Contents
 - [Technologies Used](#Technologies_Used)
 - [Installation Instructions](#Installation_Instructions)
 - [Dataset](#Dataset)

# Technologies Used
- Python 3.x
- Pandas - for data manipulation
- NumPy - for numerical computations
- Scikit-learn - for machine learning models
- Matplotlib - for visualizations
- Jupyter Notebook (optional, for running code in cells)

# Installation Instructions
To run this project, open the repository in Anaconda Navigator, create a new environment, and launch Jupyter Notebook. Then, open the project files and execute the code in the notebook to preprocess the data, train the model, and evaluate the predictions.

# Dataset
This project uses the Pima Indians Diabetes Database from Kaggle, which contains medical information for patients. The features in the dataset include:
| Sr. No | Columns | Description | Data Type |
| ------ | ------- | ----------- | --------- |
| 1      | Preg    | Number of times pregnant | Numerical |
| 2      | Plas    | Plasma glucose concentration at 2h in an oral glucose tolerance test | Numerical |
| 3      | Pres    | Blood Pressure | Numerical |
| 4      | Skin    | Skin Thickness | Numerical |
| 5      | Test    | 2-h serum insulin | Numerical |
| 6      | Mass    | Body Mass Index | Numerical |
| 7      | Pedi    | Diabetes pedigree function (Indicates likelihood of diabetes based on family history) | Categorical |
| 8      | Age     | Age in years | Numerical |
| 9      | Class   | Outcome (0 for No, 1 for Yes) | Categorical |
