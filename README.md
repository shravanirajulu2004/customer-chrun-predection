📊 Customer Churn Prediction System
📌 Project Overview

This project implements an end-to-end Customer Churn Prediction system using machine learning to identify customers who are likely to leave a service. In addition to prediction, the project focuses on analyzing and visualizing churn drivers to support data-driven business decisions.

🎯 Objective

Predict customer churn using historical customer data

Understand and explain the key factors contributing to churn

Present insights through an interactive business dashboard

🛠️ Tech Stack

Python – Data processing and modeling

Pandas & NumPy – Data manipulation

Scikit-learn – Machine learning (Logistic Regression, evaluation metrics)

Power BI – Data visualization and dashboarding

📂 Dataset

Source: Telco Customer Churn Dataset (Kaggle)

Each record represents a customer with demographic details, service usage, billing information, and churn status.

⚙️ Project Workflow

Data Loading & Exploration

Loaded customer data and analyzed structure, missing values, and churn distribution.

Data Cleaning & Preprocessing

Handled missing values, converted categorical variables to numerical format, and prepared data for modeling.

Model Building

Trained a Logistic Regression model to predict customer churn.

Split data into training and testing sets.

Model Evaluation

Evaluated model performance using precision, recall, F1-score, and accuracy.

Visualization & Insights

Built an interactive Power BI dashboard to analyze churn patterns and key drivers.

📈 Key Insights

Customers on month-to-month contracts show significantly higher churn.

Higher average monthly charges are associated with increased churn risk.

Long-term contracts help improve customer retention.

📊 Power BI Dashboard

The dashboard includes:

Overall churn distribution

Churn by contract type

Average monthly charges by churn status

Interactive slicers for deeper analysis

📁 Project Structure
customer_churn_project/
│
├── data/              # Dataset (CSV)
├── notebooks/         # Jupyter notebooks for analysis and modeling
├── model/             # Saved trained model
├── powerbi/           # Power BI dashboard file
└── README.md

🚀 Conclusion

This project demonstrates a complete data-to-insight pipeline, combining machine learning with business intelligence to address a real-world problem. It highlights how predictive analytics and visualization can work together to support customer retention strategies.
