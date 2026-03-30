HEALTHCARE PATIENT ANALYSIS SYSTEM (SYNTHETIC DATA)

PROJECT OVERVIEW

The Healthcare Patient Analysis System is a data analysis project that generates and analyzes synthetic patient health records. The system creates a dataset of 10,000 patients with important health parameters such as age, gender, blood pressure, sugar level, cholesterol, and heart rate.

The goal of this project is to perform Exploratory Data Analysis (EDA) to understand patterns in healthcare data, identify high-risk patients, and visualize relationships between different health parameters.

Since real healthcare datasets are restricted due to privacy concerns, this project uses randomly generated synthetic data for analysis and learning purposes.

PROBLEM STATEMENT

Healthcare institutions generate large volumes of patient data every day. Analyzing this data manually is time-consuming and inefficient.

Additionally, real patient datasets are not easily accessible for academic purposes due to privacy and security regulations. Therefore, this project generates synthetic healthcare data and analyzes it to identify health risks and patterns.

DATASET DESCRIPTION

The dataset contains 10,000 synthetic patient records with the following columns:

| COLUMN         | DESCRIPTION                   |
| -------------- | ----------------------------- |
| Patient_ID     | Unique patient ID             |
| Age            | Patient age (20–80 years)     |
| Gender         | Male / Female                 |
| Blood_Pressure | Blood pressure level (80–180) |
| Sugar_Level    | Blood sugar level (70–200)    |
| Cholesterol    | Cholesterol level (150–300)   |
| Heart_Rate     | Heart rate (60–120)           |

PROJECT OBJECTIVES

The main objectives of this project are:

Generate a large synthetic healthcare dataset

Perform data cleaning and preprocessing

Handle missing values and validate data ranges

Perform statistical analysis such as mean, median, mode, and standard deviation

Analyze patient health metrics:

Blood pressure

Sugar level

Cholesterol

Heart rate

Classify patients into risk levels

Low Risk

Medium Risk

High Risk

Identify high-risk patients

Perform age-group and gender-based analysis

Study relationships between health variables

Visualize the dataset using charts and graphs

DATA CLEANING STEPS

The following data cleaning operations were performed:

Checked missing values using isnull()

Filled missing numeric values using mean

Standardized gender values

Validated health parameter ranges

Removed duplicate patient IDs

Ensured correct data types for numeric columns

RISK CLASSIFICATION

Patients are classified into three categories based on health parameters:
