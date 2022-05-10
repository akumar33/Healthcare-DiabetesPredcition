# Healthcare-DiabetesPredcition

## **Problem Statement**
- NIDDK (National Institute of Diabetes and Digestive and Kidney Diseases) research creates knowledge about and treatments for the most chronic, costly, and consequential diseases.
- The dataset used in this project is originally from NIDDK.

## Objective

- Predict whether a patient has diabetes or not
- Build a model to accurately predict whether the patients in the dataset have diabetes or not

## Dataset Description
Dataset contains certain diagnostic measurements of several medical predictor variables and one target variable (Outcome). 
The independent variables in this data set are - Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration in an oral glucose tolerance test
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skinfold thickness (mm)
- Insulin: Two hour serum insulin
- BMI: Body Mass Index
- DiabetesPedigreeFunction: Diabetes pedigree function
- Age: Age in years
- Outcome: Class variable (either 0 or 1). 268 of 768 values are 1, and the others are 0

268 of 768 values are 1, and the others are 0

## Tasks:
- Import required libraries
- Load dataset

### Data Exploration:
3.1 Perform descriptive analysis:
- 3.1.1 Head
- 3.1.2 Shape
- 3.1.3 Types of columns
- 3.1.4 Summary

### 3.2. Data Pre-processing/ Data cleaning:
- 3.2.1 Duplicate value check
- 3.2.2 Missing value/ Null value check
- 3.2.3 Check distributions of each feature before treating missing values usign histogram
- 3.2.4 Check correlation
- 3.2.5 Treat missing values

### Data Visualization:
- 4.1 Count plot to see if dataset is balanced
- 4.2 Histogram to check if the data distribution is Normal / Skewed
- 4.3 Box plot to check and handle outliers
- 4.4 Scatter plots to understand relationship between variables

### Check correlation using heatmap after treating missing values and outliers

### Data Transformation:
- Normalization

### Split data to train and test data

### Data Modelling:
- 8.1 Build model with train data
- 8.2 Predict for test data using model
- 8.3 Check model accuarcy
- 8.4 Compare with other models

### Dashboard/ Data Reporting:
- a. Pie chart to describe the diabetic or non-diabetic population
- b. Scatter charts between relevant variables to analyze the relationships
- c. Histogram or frequency charts to analyze the distribution of the data
- d. Heatmap of correlation analysis among the relevant variables
- e. Create bins of these age values: 20-25, 25-30, 30-35, etc. Analyze different variables for these age brackets using a bubble chart.
