Below is a **clean, consistent rewrite** of your **Customer Churn project**, structured and worded to **match the tone, flow, and clarity of your Sales & Customer Insights Dashboard**. This is portfolio-ready and recruiter-friendly—no fluff, no noise.

---

# 📊 Customer Churn Prediction & Analysis Dashboard

## 🔹 Project Overview

This project analyzes **customer churn behavior** and predicts customers at risk of leaving using a real-world **telecom dataset**.
It demonstrates a **complete end-to-end Machine Learning & Analytics workflow**:

✅ Data Cleaning & Preprocessing using Python
✅ Exploratory Data Analysis (EDA)
✅ Machine Learning using Scikit-learn
✅ Model Evaluation & Validation
✅ Data Visualization using Power BI
✅ Business Insight Generation

The goal is to help businesses:

* Identify customers at high risk of churn
* Understand key factors driving churn
* Support data-driven customer retention strategies

====================================================================================================================

## 🔹 Tools & Technologies Used

| Purpose                       | Tool                   |
| ----------------------------- | ---------------------- |
| Data Cleaning & Preprocessing | Python (Pandas, NumPy) |
| Machine Learning              | Scikit-learn           |
| Model Evaluation              | Classification Metrics |
| Data Visualization            | Power BI               |
| Data Files                    | CSV                    |
| Model Storage                 | Joblib                 |
| Hosting                       | GitHub                 |

====================================================================================================================

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

====================================================================================================================

## 🔹 Step 1: Data Loading & Exploration (Python)

The Telco Customer Churn dataset was loaded and explored to understand:

* Dataset structure
* Data types
* Missing values
* Churn distribution

Initial EDA ensured data quality and helped identify preprocessing requirements.

📄 File Used:
notebooks/01_load_and_check_data.ipynb

---

## 🔹 Step 2: Data Cleaning & Preprocessing

Using **Pandas**, the following steps were performed:

* Converted `TotalCharges` to numeric format
* Removed rows with missing values
* Encoded the target variable (Churn)
* Applied one-hot encoding to categorical features

This step prepared the dataset for machine learning.

---

## 🔹 Step 3: Machine Learning Model (Scikit-learn)

A **Logistic Regression** model was trained to predict customer churn.

Steps included:

* Train-test split (80/20)
* Model training using Scikit-learn
* Prediction on unseen data

📄 Model Saved As:
model/churn_model.pkl

---

## 🔹 Step 4: Model Evaluation

The model was evaluated using standard classification metrics:

✅ Accuracy
✅ Precision
✅ Recall
✅ F1-Score

The results provide a reliable baseline churn prediction model and a foundation for further optimization.

---

## 🔹 Step 5: Power BI Dashboard

An interactive **Power BI dashboard** was built to visualize churn patterns and customer behavior.

### Dashboard Visuals:

📊 Customer Churn Count
📑 Churn by Contract Type
💰 Average Monthly Charges by Churn Status
🎛️ Interactive slicers for detailed analysis

📁 File:
powerbi/churn_dashboard.pbix

---

## 🔹 Key Business Insights

✔️ Customers on month-to-month contracts show the highest churn
✔️ Higher monthly charges strongly correlate with churn
✔️ Long-term contracts significantly improve retention
✔️ Churn analysis enables targeted, data-driven retention strategies

---

## 🔹 Skills Demonstrated

✅ Data Cleaning & Preprocessing
✅ Exploratory Data Analysis (EDA)
✅ Machine Learning with Scikit-learn
✅ Model Evaluation & Interpretation
✅ Power BI Dashboard Design
✅ End-to-End Analytics & ML Project

---

## 🔹 How to Run This Project

1️⃣ Run the Jupyter Notebook

```
notebooks/01_load_and_check_data.ipynb
```

2️⃣ Open Power BI Dashboard

```
powerbi/churn_dashboard.pbix
```

