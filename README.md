Healthcare Patient Analysis System (Synthetic Data)

Project Overview

     * The Healthcare Patient Analysis System is a data analysis project that generates and analyzes synthetic patient health records. The system creates a dataset of 10,000 patients with important health parameters such as age, gender, blood pressure, sugar level, cholesterol, and heart rate.
     * The goal of this project is to perform Exploratory Data Analysis (EDA) to understand patterns in healthcare data, identify high-risk patients, and visualize relationships between different health parameters.
     * Since real healthcare datasets are restricted due to privacy concerns, this project uses randomly generated synthetic data for analysis and learning purposes.

Problem Statement

       * Healthcare institutions generate large volumes of patient data every day. Analyzing this data manually is time-consuming and inefficient.        
       * Additionally, real patient datasets are not easily accessible for academic purposes due to privacy and security regulations. Therefore, this project generates synthetic healthcare data and analyzes it to identify health risks and patterns.

Dataset Description


  * The dataset contains 10,000 synthetic patient records with the following columns:

* Patient_ID – Unique patient ID
* Age – Patient age (20 to 80 years)
* Gender – Male or Female
* Blood_Pressure – Blood pressure level (80 to 180)
* Sugar_Level – Blood sugar level (70 to 200)
* Cholesterol – Cholesterol level (150 to 300)
* Heart_Rate – Heart rate (60 to 120)

Project Objectives

The main objectives of this project are:

• Generate a large synthetic dataset representing patient health records
• Perform data cleaning and preprocessing
• Handle missing values and validate data ranges
• Perform statistical analysis such as mean, median, mode, and standard deviation
• Analyze patient health metrics including blood pressure, sugar level, cholesterol, and heart rate
• Classify patients into risk levels (Low, Medium, High)
• Identify high-risk patients
• Perform age-group and gender-based analysis
• Study relationships between health variables
• Visualize the dataset using different charts and graphs

Data Cleaning Steps

The following data cleaning operations were performed:

• Checked missing values using isnull()
• Filled missing numeric values using mean
• Standardized gender values
• Validated health parameter ranges
• Removed duplicate patient IDs
• Ensured correct data types for numeric columns

Risk Classification

Patients are classified into three categories based on health parameters:

Low Risk – Normal health values
Medium Risk – Slightly higher values
High Risk – Dangerous health levels

High risk conditions include:

Blood Pressure greater than 140
Sugar Level greater than 180
Cholesterol greater than 240

Data Analysis Performed

The following analyses were performed:

• Descriptive statistics (mean, median, mode, standard deviation)
• Distribution analysis of blood pressure, sugar level, cholesterol, and heart rate
• Age group analysis
• Gender-wise risk analysis
• Correlation analysis between health parameters

Data Visualization

The project includes several visualizations such as:

Bar Chart – Risk level distribution
Pie Chart – Percentage of risk levels
Histogram – Age distribution
Scatter Plot – Age vs Blood Pressure
Box Plot – Cholesterol distribution and outliers
Heatmap – Correlation between variables

Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn

Expected Outcome

The analysis helps to:

• Understand patterns in healthcare data
• Detect high-risk patients
• Study relationships between health parameters
• Support better healthcare monitoring and decision-making

Conclusion

This project demonstrates how healthcare data can be analyzed using Python and data science techniques. By generating synthetic data and applying Exploratory Data Analysis, meaningful insights can be derived that help understand patient health conditions and risk levels.
