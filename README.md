❤️ Heart Disease Exploratory Data Analysis (EDA)
📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early analysis and identification of risk factors can significantly improve prevention and treatment outcomes.

This project performs a comprehensive Exploratory Data Analysis (EDA) on a Heart Disease dataset to uncover meaningful patterns, relationships, and insights that may help in understanding factors contributing to heart disease.

The analysis focuses on:

Understanding data structure

Identifying key risk factors

Visualizing relationships between features

Drawing insights useful for further Machine Learning modeling

🎯 Objectives

Understand the distribution of patient health attributes

Identify correlations between medical features and heart disease

Detect patterns, trends, and anomalies in the dataset

Prepare insights that can guide predictive model development

📂 Dataset Information

The dataset contains medical attributes commonly used to predict heart disease.

🔑 Key Features
Feature	      Description
age	          Age of the patient
sex	          Gender (1 = Male, 0 = Female)
cp	          Chest pain type
trestbps	    Resting blood pressure
chol	        Serum cholesterol (mg/dl)
fbs	          Fasting blood sugar
restecg	      Resting ECG results
thalach	      Maximum heart rate achieved
exang	        Exercise-induced angina
oldpeak	      ST depression
slope	        Slope of peak exercise ST segment
ca	          Number of major vessels
thal	        Thalassemia
target	      Heart disease presence (1 = Yes, 0 = No)

🛠️ Tools & Libraries Used

Python

NumPy – Numerical computations

Pandas – Data manipulation

Matplotlib – Data visualization

Seaborn – Statistical plotting

Jupyter Notebook

🔍 Exploratory Data Analysis Steps
1️⃣ Data Loading & Inspection

Loaded dataset into Pandas DataFrame

Checked shape, data types, and column names

Reviewed first and last few records

2️⃣ Data Cleaning

Checked for missing values

Verified duplicate records

Ensured correct data formats

3️⃣ Univariate Analysis

Distribution of numerical features (histograms)

Count plots for categorical features

Target variable balance analysis

4️⃣ Bivariate Analysis

Feature vs Target comparisons

Gender-wise and age-wise heart disease analysis

Chest pain type impact on heart disease

5️⃣ Correlation Analysis

Heatmap to visualize feature correlations

Identified highly influential features

Removed multicollinearity concerns (if any)

6️⃣ Visual Insights

Box plots to detect outliers

Pair plots for relationship exploration

Trend analysis using grouped plots

📊 Key Insights

Age and maximum heart rate show strong relationships with heart disease

Certain chest pain types are highly correlated with disease presence

Exercise-induced angina significantly increases risk

Males show higher heart disease prevalence compared to females

Cholesterol alone is not a strong predictor without other features

🚀 Future Scope

Apply feature scaling and selection

Build Machine Learning models (Logistic Regression, Random Forest, XGBoost)

Perform model evaluation and comparison

Deploy a prediction system using Streamlit

📁 Project Structure
📦 Heart-Disease-EDA
 ┣ 📜 HDPD_asifshethwala.ipynb
 ┣ 📜 README.md


Run HDPD_asifshethwala.ipynb


