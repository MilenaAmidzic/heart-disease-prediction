# heart-disease-prediction
Heart disease prediction using logistic regression and clinical dataset
# Heart Disease Prediction using Machine Learning

This project explores clinical data to build a machine learning model capable of predicting the presence of heart disease.

## Project Overview

The dataset contains clinical variables such as age, cholesterol level, chest pain type, resting ECG results, and exercise-related measurements.

The goal of the project is to:

• perform exploratory data analysis (EDA)  
• understand relationships between clinical variables  
• build a predictive model for heart disease  
• evaluate model performance using standard machine learning metrics  

## Exploratory Data Analysis

The analysis includes:

- distribution analysis of numerical variables  
- categorical variable exploration  
- correlation matrix visualization  
- feature relationships with the target variable  

These steps help identify potential predictors of heart disease.

## Machine Learning Model

A Logistic Regression model was used as a baseline classifier.

The dataset was split into training and testing sets (80/20).

## Model Performance

Accuracy: **~79%**

Evaluation metrics include:

- confusion matrix
- precision and recall
- ROC curve
- AUC score

The model achieved an **AUC score of 0.84**, indicating good ability to distinguish between patients with and without heart disease.

## Key Predictive Features

The model suggests that several variables have strong predictive influence, including:

- chest pain type (cp)
- ST slope
- resting ECG results
- exercise induced angina
- ST depression (oldpeak)

These features are commonly associated with cardiovascular diagnostic indicators.

## Technologies Used

Python  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Scikit-learn  

## Project Structure

heart_disease_prediction.ipynb – full analysis and modeling workflow

## Author

Milena Zamurović
