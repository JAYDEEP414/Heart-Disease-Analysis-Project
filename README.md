# Heart Disease Analysis Project

## Project Overview
This project analyzes a synthetic healthcare dataset to identify key risk factors associated with heart disease. The analysis follows a complete data analytics workflow, including data cleaning, preprocessing, exploratory data analysis (EDA), feature engineering, and interactive dashboard development in Power BI.

The objective is to understand how demographic, clinical, and lifestyle factors such as age, cholesterol, BMI, smoking habits, diabetes, stress levels, sleep patterns, and physical activity influence the likelihood of heart disease.

## Business Objective
The goal of this project is to:
- Analyze patient demographics and medical indicators.
- Identify major heart disease risk factors.
- Segment high-risk patient groups.
- Build an executive dashboard for healthcare decision-making.
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
- Power BI
- GitHub

## Project Workflow

### 1. Data Cleaning and Preprocessing
- Loaded the dataset in Jupyter Notebook.
- Checked data types and summary statistics.
- Removed duplicate records.
- Handled missing values using median and mode imputation.
- Standardized categorical values.
- Created additional analytical features.

### 2. Exploratory Data Analysis (EDA)
- Analyzed heart disease distribution.
- Visualized age, cholesterol, BMI, and blood pressure trends.
- Studied the impact of smoking, diabetes, stress, sleep, and physical activity.
- Generated correlation matrices and boxplots.
- Extracted meaningful healthcare insights.

### 3. Feature Engineering
Created additional columns to improve analysis:
- Age Group
- BMI Category
- Cholesterol Category
- Risk Level

### 4. Power BI Dashboard
Developed an interactive dashboard featuring:
- KPI cards for total patients, heart disease cases, and disease percentage
- Gender-wise and age group analysis
- Smoking and diabetes impact analysis
- Stress and sleep pattern visualizations
- Scatter plot for age vs cholesterol
- Interactive slicers for dynamic filtering

## Key Insights
- Heart disease prevalence increases with age.
- Higher cholesterol and blood pressure are associated with greater risk.
- Smoking and diabetes significantly increase heart disease likelihood.
- Elevated stress and reduced sleep correlate with higher disease rates.
- Regular physical activity is associated with lower heart disease prevalence.

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
├── powerbi/
│   └── Heart_Disease_Analysis_Dashboard.pbix
│
├── images/
│   └── dashboard_screenshot.png
│
└── README.md
