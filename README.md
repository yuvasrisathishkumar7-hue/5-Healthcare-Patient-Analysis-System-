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

| RISK LEVEL  | DESCRIPTION              |
| ----------- | ------------------------ |
| Low Risk    | Normal health values     |
| Medium Risk | Slightly elevated values |
| High Risk   | Dangerous health levels  |

HIGH RISK CONDITIONS

Blood Pressure > 140

Sugar Level > 180

Cholesterol > 240

DATA ANALYSIS PERFORMED

The following analyses were conducted:

Descriptive statistics

Mean

Median

Mode

Standard deviation

Distribution analysis of:

Blood pressure

Sugar level

Cholesterol

Heart rate

Age group analysis

Gender-wise risk analysis

Correlation analysis between health parameters

DATA VISUALIZATION

The project includes several visualizations:


| CHART        | PURPOSE                               | GRAPH UNDERSTANDING / KEY POINTS                                                                                                                                                       |
| ------------ | ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Bar Chart    | Risk level distribution               | Shows how many patients fall into Low, Medium, and High risk categories. Helps quickly identify which risk group has the highest number of patients.                                   |
| Pie Chart    | Percentage of risk levels             | Displays the percentage share of each risk category. Useful for understanding the proportion of patients in each risk level.                                                           |
| Histogram    | Age distribution                      | Shows how patient ages are distributed across the dataset. Helps identify which age group has the most patients.                                                                       |
| Scatter Plot | Age vs Blood Pressure                 | Displays the relationship between age and blood pressure. Helps observe whether blood pressure increases with age.                                                                     |
| Box Plot     | Cholesterol distribution and outliers | Shows the spread of cholesterol levels and detects outliers. Helps identify unusually high or low cholesterol values.                                                                  |
| Heatmap      | Correlation between variables         | Visualizes correlation between health parameters such as age, blood pressure, sugar level, cholesterol, and heart rate. Helps identify strong or weak relationships between variables. |

BAR CHART

<img width="446" height="399" alt="image" src="https://github.com/user-attachments/assets/4d1d5ae4-7069-4421-82a2-7580c58752bf" />



PIE CHART

<img width="328" height="309" alt="image" src="https://github.com/user-attachments/assets/5e5027c2-fd78-4008-83fb-5bdf77b6b3b7" />




HISTOGRAM

<img width="448" height="346" alt="image" src="https://github.com/user-attachments/assets/4662ec73-d09d-41a8-ad9c-20ee73cf9090" />



SCATTER PLOT

<img width="461" height="348" alt="image" src="https://github.com/user-attachments/assets/08d30348-dc49-45d4-a697-bb83683b855d" />




BOX PLOT 

<img width="410" height="344" alt="image" src="https://github.com/user-attachments/assets/56dc7e67-de7b-4951-9f6b-dde259c6b71b" />



HEATMAP

<img width="484" height="405" alt="image" src="https://github.com/user-attachments/assets/ed986bdd-8d1b-450b-ac43-ff7ca6035a5c" />




TECHNOLOGIES USED

Python

Pandas

NumPy

Matplotlib

Seaborn

EXPECTED OUTCOME

The analysis helps to:

Understand patterns in healthcare data

Detect high-risk patients

Study relationships between health parameters

Support better healthcare monitoring and decision-making

CONCLUSION

This project demonstrates how healthcare data can be analyzed using Python and data science techniques. By generating synthetic data and applying Exploratory Data Analysis (EDA), meaningful insights can be derived to understand patient health conditions and identify potential health risks.

