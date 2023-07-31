# Diabetes Analysis using Machine Learning SVM Approach

## Introduction
- This project aims to predict whether a patient has diabetes or not based on diagnostic measures     from their medical records. The data is taken from the Pima Indians Diabetes dataset available on    Kaggle. It contains medical records of Pima Indian patients with various features like glucose level, blood pressure, BMI, age etc.

- The goal is to train a machine learning model to predict the diabetes outcome (0 for No Diabetes, 1 for Diabetes) based on the other features. A support vector machine (SVM) model is chosen for this binary classification task.

The data contains medical records of Pima Indian patients with the following features:

- Pregnancies - Number of times pregnant 
- Glucose - Plasma glucose concentration 
- BloodPressure - Diastolic blood pressure (mm Hg)
- SkinThickness - Triceps skin fold thickness (mm)
- Insulin - 2-Hour serum insulin (mu U/ml)
- BMI - Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction - Diabetes pedigree function
- Age - Age in years
- Outcome - Class variable (0: No Diabetes, 1: Diabetes)

## Libraries Used

The following Python libraries are used in this project:

- pandas - for data manipulation
- numpy - for numerical processing
- sklearn - for preprocessing, model training and evaluation
- matplotlib - for plotting graphs
- seaborn - for visualizations 

## Data Exploration
- The data is loaded and initially explored to understand the features. Summary statistics and visualizations are generated to analyze feature distributions, correlations, outliers etc. This provides insights like glucose levels being a potentially useful predictor of diabetes.

## Data Preprocessing
- The data is split into train and test sets for modeling. The features are scaled to have zero mean and unit variance to help with model convergence.

## Model Training
- A support vector machine (SVM) model with a linear kernel is trained on the training data. SVM is chosen due to its ability to find an optimal separating hyperplane between the two classes.

## IMAGES 

![Graph](statistics.png)

![Graph](lo.png)

## Model Evaluation
- The performance of the model is evaluated on the test set using classification accuracy as the metric. The model achieves reasonable performance.

## Conclusion
The project demonstrates using SVM for predicting diabetes risk from medical records. The model achieves decent accuracy but further tuning could improve performance. The data exploration also provides insights into important predictors like glucose levels. As future work, additional models could be tried and hyperparameters could be optimized.
 
