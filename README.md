# Diabetes-Prediction-Machine-Learning-Pr-2-
So i made a ML project for predicting Diabetes in a patients body with the help of PIMA dataset in diabetes.

So in this project i am using the Diabetes dataset provided PIMA which is actually available online for free as well. u can also use ur own database as well. 
but now for instance i am using the available one.

--> Project Overview

Diabetes Prediction Using Machine Learning is a predictive healthcare application designed to estimate whether an individual is likely to have diabetes based on relevant medical and physiological parameters.

The system uses supervised machine learning to learn patterns from historical patient data. A Support Vector Machine (SVM) classifier is trained on the dataset and subsequently used to classify new patient records into two categories:

Diabetic
Non-Diabetic

The project demonstrates how machine learning can be applied to healthcare data for early risk assessment and decision support

-->Technologies Used: 
Python, Numpy, Pandas, Scikit Learn, Matplotlib, Seaborn, VSC 
Support Vector Machine (SVM): primary classification algorithm

--> Dataset Shows and compares: 
Number of pregnancies
Glucose concentration
Blood pressure
Skin thickness
Insulin level
Body Mass Index (BMI)
Diabetes Pedigree Function
Age

--> WORKFLOW:
Medical Dataset → Data Preprocessing → Feature Scaling → Train/Test Split → SVM Training → Model Evaluation → Prediction

                 ┌───────────────────┐
                 │   Diabetes Dataset │
                 └─────────┬─────────┘
                           ↓
                 ┌───────────────────┐
                 │ Data Preprocessing│
                 └─────────┬─────────┘
                           ↓
                 ┌───────────────────┐
                 │ Feature Scaling   │
                 └─────────┬─────────┘
                           ↓
                 ┌───────────────────┐
                 │ Train/Test Split  │
                 └─────────┬─────────┘
                           ↓
                 ┌───────────────────┐
                 │   SVM Classifier  │
                 └─────────┬─────────┘
                           ↓
                 ┌───────────────────┐
                 │ Model Evaluation  │
                 └─────────┬─────────┘
                           ↓
                 ┌───────────────────┐
                 │ New Patient Input │
                 └─────────┬─────────┘
                           ↓
                 ┌───────────────────┐
                 │ Diabetes Prediction│
                 └───────────────────┘


