# Diabetes-Prediction-Machine-Learning-Project

Project Overview
This project aims to predict whether a person has diabetes or not using a machine learning model. The project is a classification problem solved using the Support Vector Machine (SVM) algorithm. The model is trained on a dataset of diagnostic measurements and has an accuracy score of 77.7% on the test data.

Dataset
The dataset used is diabetes.csv, which contains various health metrics and an Outcome column indicating if a person is diabetic (1) or not (0). The columns are:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Outcome

Technology Stack
Language: Python

Libraries:

pandas for data manipulation and analysis

numpy for numerical operations

scikit-learn for machine learning algorithms and model evaluation (specifically StandardScaler, train_test_split, svm, and accuracy_score)

Environment: Jupyter Notebook

Project Workflow
Data Loading: The diabetes.csv dataset is loaded into a pandas DataFrame.

Data Analysis: Initial analysis is performed to understand the dataset's structure and contents.

Data Standardization: Features are standardized using StandardScaler to bring them to a common scale.

Model Training: The data is split into training and testing sets, and an SVM classifier is trained on the training data.

Model Evaluation: The model's performance is evaluated on both training and test data, with an accuracy score of 77.7% on the test data.
