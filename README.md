# 📊 Customer Churn Prediction & Analysis Dashboard
## 🔹 Project Overview

This project focuses on predicting customer churn and analyzing churn behavior using a real-world telecom dataset.
It demonstrates a complete end-to-end Machine Learning & Analytics workflow:

✅ Data Cleaning & Preprocessing using Python
✅ Exploratory Data Analysis (EDA)
✅ Machine Learning using Scikit-learn
✅ Model Evaluation & Validation
✅ Data Visualization using Power BI
✅ Business Insight Generation

The goal is to help businesses:

Identify customers at high risk of churn

Understand key churn drivers

Support data-driven customer retention strategies

## 🔹 Tools & Technologies Used

Data Cleaning & Processing	Python (Pandas, NumPy)
Machine Learning	Scikit-learn
Model Evaluation	Classification Metrics
Data Visualization	Power BI
Data Files	CSV
Model Storage	Joblib

## 🔹 Project Folder Structure
customer_churn_project/
│
├── data/
│   └── churn.csv
│
├── notebooks/
│   └── 01_load_and_check_data.ipynb
│
├── model/
│   └── churn_model.pkl
│
├── powerbi/
│   └── churn_dashboard.pbix
│
└── README.md

## 🔹 Step 1: Data Loading & Exploration (Python)

The Telco Customer Churn dataset was loaded and explored to understand:

Data structure

Column types

Missing values

Churn distribution

Initial checks ensured the dataset was suitable for machine learning.

📄 File Used:
notebooks/01_load_and_check_data.ipynb

## 🔹 Step 2: Data Cleaning & Preprocessing

The following preprocessing steps were performed using Pandas:

Converted TotalCharges to numeric format

Removed rows with missing values

Encoded the target variable (Churn)

Converted categorical variables using one-hot encoding

This step prepared the dataset for model training.

## 🔹 Step 3: Machine Learning Model (Scikit-learn)

A Logistic Regression model was trained to predict customer churn.

Steps included:

Train-test split (80/20)

Model training using Scikit-learn

Performance evaluation using classification metrics

## 📄 Output:
model/churn_model.pkl

## 🔹 Step 4: Model Evaluation

The model was evaluated using:

Precision

Recall

F1-score

Accuracy

The results provided a reliable baseline churn prediction model, highlighting areas for future improvement.

## 🔹 Step 5: Power BI Dashboard

An interactive Power BI dashboard was created to visualize churn patterns and customer behavior.

## Dashboard Visuals:

📊 Customer Churn Count
📑 Churn by Contract Type
💰 Average Monthly Charges by Churn Status
🎛️ Interactive slicers for deeper analysis

📁 File:
powerbi/churn_dashboard.pbix

## 🔹 Key Business Insights

✔️ Customers on month-to-month contracts have the highest churn
✔️ Higher monthly charges are strongly associated with churn
✔️ Long-term contracts help improve customer retention
✔️ Churn insights can guide targeted retention strategies

## 🔹 Skills Demonstrated

✅ Data Cleaning & Preprocessing
✅ Machine Learning with Scikit-learn
✅ Model Evaluation & Interpretation
✅ Power BI Dashboard Design
✅ Business Insight Generation
✅ End-to-End Analytics Project

## 🔹 How to Run This Project

1️⃣ Open Jupyter Notebook and run analysis

notebooks/01_load_and_check_data.ipynb


2️⃣ Load dataset into Power BI

Open churn_dashboard.pbix

Refresh data if required
