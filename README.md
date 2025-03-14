# Diabetics-Prediction-Using-Logistics-Regression
Overview

This project implements a Diabetes Prediction Model using Logistic Regression in Google Colab. The dataset is imported directly from Kaggle using the API.

Dataset

Source: Kaggle - Diabetes Dataset

File Used: diabetes.csv

Attributes:

Pregnancies

Glucose

Blood Pressure

Skin Thickness

Insulin

BMI

Diabetes Pedigree Function

Age

Outcome (Target Variable: 0 = No Diabetes, 1 = Diabetes)

Features

Data import from Kaggle via API

Data preprocessing and standardization

Model training using Logistic Regression

Model evaluation using Accuracy, Confusion Matrix, and Classification Report

Saving and downloading the trained model

Installation & Usage

Clone the Repository:

git clone https://github.com/yourusername/diabetes-prediction.git
cd diabetes-prediction

Run on Google Colab:

Upload kaggle.json for dataset access

Run the diabetes_logistic_colab.py script

Saving and Downloading Model

The trained model is saved as diabetes_model.pkl and can be downloaded locally.

The scaler used for normalization is saved as scaler.pkl.

Dependencies

The following Python libraries are required:

!pip install kaggle pandas numpy matplotlib seaborn scikit-learn joblib

Evaluation Metrics

Accuracy Score

Confusion Matrix

Classification Report

License

This project is licensed under the MIT License.
