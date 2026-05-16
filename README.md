# Heart Disease Analysis Project

## Project Overview
This project analyzes a synthetic healthcare dataset to identify key risk factors associated with heart disease. The analysis covers the complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), SQL-based business analysis, interactive dashboard development in Power BI, and feature engineering.

The objective of this project is to help healthcare organizations understand how demographic, clinical, and lifestyle factors such as age, cholesterol, BMI, smoking habits, diabetes, stress levels, sleep patterns, and physical activity influence the likelihood of heart disease.

## Business Objective
The goal of this project is to:
- Analyze patient demographics and medical indicators.
- Identify major heart disease risk factors.
- Segment high-risk patient groups.
- Build an executive dashboard for decision-making.
- Demonstrate end-to-end data analytics skills.

## Dataset Information
The dataset is a synthetic healthcare dataset created for portfolio and educational purposes. It contains approximately 5,000 patient records and includes demographic, medical, and lifestyle attributes.

### Key Columns
- Patient_ID
- Age
- Gender
- Chest_Pain_Type
- Resting_Blood_Pressure
- Cholesterol
- Fasting_Blood_Sugar
- Resting_ECG
- Max_Heart_Rate
- Exercise_Induced_Angina
- ST_Depression
- Slope_of_ST
- Number_of_Major_Vessels
- Thalassemia
- Smoking
- Alcohol_Intake
- BMI
- Physical_Activity_Level
- Diabetes
- Family_History
- Stress_Level
- Sleep_Hours
- Heart_Disease

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- MySQL
- Power BI
- GitHub

## Project Workflow

### 1. Data Cleaning and Preprocessing
- Loaded the dataset in Jupyter Notebook.
- Checked data types and summary statistics.
- Removed duplicate records.
- Handled missing values using median and mode imputation.
- Standardized categorical text values.
- Created engineered features such as Age Group and BMI Category.

### 2. Exploratory Data Analysis (EDA)
- Analyzed target variable distribution.
- Visualized age, cholesterol, and BMI distributions.
- Studied relationships between smoking, diabetes, and heart disease.
- Generated correlation matrix and boxplots.
- Extracted business insights from patient characteristics.

### 3. SQL Analysis
- Imported the cleaned dataset into MySQL.
- Solved 20 business-driven queries to answer healthcare questions such as:
  - Total number of patients
  - Heart disease prevalence
  - Gender-wise comparisons
  - Age group analysis
  - High-risk patient identification

### 4. Power BI Dashboard
Developed an interactive dashboard with:
- KPI cards for total patients, heart disease cases, and heart disease percentage
- Gender-wise heart disease distribution
- Age group analysis
- Smoking and diabetes impact
- Stress and sleep pattern analysis
- Scatter plot for age vs cholesterol
- Slicers for dynamic filtering

### 5. Feature Engineering
Created additional columns to improve analysis:
- Age Group
- BMI Category
- Cholesterol Category
- Risk Level

## Key Insights
- Heart disease prevalence increases with age.
- Higher cholesterol and blood pressure are associated with increased risk.
- Smoking and diabetes significantly increase heart disease rates.
- Elevated stress and reduced sleep correlate with higher risk.
- Physical activity is associated with lower heart disease prevalence.

## Project Structure
```text
Heart-Disease-Analysis-Project/
│
├── data/
│   ├── Heart_Disease_Dataset.csv
│   ├── Cleaned_Dataset.csv
│   └── Cleaned_Dataset_Enhanced.csv
│
├── notebooks/
│   └── Heart_Disease_Data_Cleaning_EDA.ipynb
│
├── sql/
│   └── heart_disease_analysis.sql
│
├── powerbi/
│   └── Heart_Disease_Analysis_Dashboard.pbix
│
├── images/
│   └── dashboard_screenshot.png
│
└── README.md
