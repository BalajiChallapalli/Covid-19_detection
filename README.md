
# Covid 19 Detection system
This project aims to develop a system for detecting COVID-19 infections using supervised learning techniques, specifically Logistic Regression and K-Nearest Neighbors (KNN). The system analyzes medical data to accurately identify whether an individual is infected with COVID-19.


## Table of content

1.[Introduction]()

2.[Features]()

3.[How it works]()

4.[Data]()

5.[Model Training]()







## Introduction

The COVID-19 Detection project uses advanced machine learning algorithms to provide accurate and timely identification of COVID-19 infections. By analyzing patient data, the system predicts the likelihood of infection, aiding healthcare professionals in making informed decisions.



## Features
- ### Accurate Detection: 
   Utilizes Logistic Regression and KNN to ensure high accuracy.
- ### User-Friendly Interface: 
  Easy input of patient data and quick retrieval of results.
- ### Scalable Solution: 
  Handles large datasets, suitable for hospitals and healthcare facilities.

## How It Works
- ### Data Collection: 
  Gather patient data, including symptoms, medical history, and test results.

- ### Data Preprocessing: 
  Clean and prepare the data for analysis.

- ### Feature Selection: 
  Identify relevant features for COVID-19 detection.

- ### Model Training:
  #### 1. Logistic Regression: 
     Models the probability of a binary outcome (COVID-19 positive/negative).
  #### 2. K-Nearest Neighbors (KNN): 
  Classifies based on the nearest neighbors' majority class.

- ### Model Evaluation: 
  Test models with separate datasets to evaluate performance.
  Prediction and Detection: Predict COVID-19 infection in new patients.

## Data
- ### Source: 
  Medical datasets including symptoms, medical history, and test results.

- ### Preprocessing: 
  Handling missing values, normalizing features, and selecting relevant attributes.
## Model Training
- ### Logistic Regression: 
  Implemented using sklearn.linear_model by importing LogisticRegression.
- ### K-Nearest Neighbors (KNN): 
  Implemented using sklearn.neighbors by importing KNeighborsClassifier
- ### Training Process: 
  Split data into training and testing sets, train models on training data by using test_train_split, validate on testing data.
