
# Heart Disease Prediction

This project uses a machine learning model to predict the likelihood of heart disease based on various medical attributes of a patient.

## Table of Contents

- [Introduction]
- [Dataset]
- [Installation]
- [Usage]
- [Model Evaluation]
- [Building a Predictive System]

## Introduction

Heart disease is a common and potentially fatal medical condition. Early detection and prediction can help in better patient care and management. This project aims to predict the presence or absence of heart disease based on a set of medical attributes using machine learning.

## Dataset

The dataset used for this project is sourced from 'heart.csv' and contains the following columns:

- `age`: The person's age in years
- `sex`: The person's sex (1 = male, 0 = female)
- `cp`: The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)
- `trestbps`: The person's resting blood pressure (mm Hg on admission to the hospital)
- `chol`: The person's cholesterol measurement in mg/dl
- `fbs`: The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)
- `restecg`: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)
- `thalach`: The person's maximum heart rate achieved
- `exang`: Exercise induced angina (1 = yes; 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: The slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)
- `ca`: The number of major vessels (0-3)
- `thal`: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect)
- `target`: Heart disease (0 = no, 1 = yes)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Sanjeet76/heart-disease-prediction.git
   cd heart-disease-prediction
## Usage
To train and evaluate the model:
This will load the dataset, train a logistic regression model, and evaluate its performance. You can also modify the input data in the script to make predictions for new data.

## Model Evaluation
- Accuracy on Training Data: 85.12%
- Accuracy on Test Data: 81.97%
- Mean Squared Error: 0.1803
- Receiver Operating Characteristic (ROC) curve

## Building a Predictive System
You can use the trained model to make predictions for new data.
