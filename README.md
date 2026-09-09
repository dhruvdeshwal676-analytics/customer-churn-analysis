# 📊 Customer Churn Analysis & Prediction

An end-to-end telecom customer churn analysis project using **Python, Machine Learning, and Power BI** to understand customer behavior, identify churn patterns, and predict customers who are at risk of leaving.

## 📌 Project Overview

Customer churn is a major challenge for subscription-based businesses. This project analyzes telecom customer data to understand the factors associated with customer churn and uses a Machine Learning model to identify customers who may be at risk of churning.

The project combines **Python-based data analysis and churn prediction** with an interactive **Power BI dashboard** for business-focused insights.

## 🎯 Objectives

- Analyze customer demographics and service-related characteristics.
- Identify patterns associated with customer churn.
- Prepare and transform customer data for Machine Learning.
- Build an Artificial Neural Network (ANN) model for churn prediction.
- Evaluate model performance using classification metrics.
- Identify customers who may be at higher risk of churn.
- Create a Power BI dashboard for interactive business analysis.

## 🗂️ Dataset

The project uses a telecom customer churn dataset containing **7,043 customer records and 21 variables**.

The dataset includes information related to:

- Customer demographics
- Tenure
- Contract type
- Internet service
- Payment method
- Monthly charges
- Total charges
- Customer churn status

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **TensorFlow / Keras**
- **Power BI**
- **Jupyter Notebook / Google Colab**

## 🔍 Project Workflow

### 1. Data Exploration & Cleaning

- Loaded the telecom customer dataset using Pandas.
- Examined data structure and customer attributes.
- Identified missing values in the `TotalCharges` field.
- Prepared the dataset for further analysis and modelling.

### 2. Data Preprocessing

- Encoded categorical variables using one-hot encoding.
- Separated features and target variable.
- Split the dataset into training and testing sets.
- Applied feature scaling using `StandardScaler`.

### 3. Machine Learning — ANN

An **Artificial Neural Network (ANN)** model was developed to predict customer churn.

The model was trained using the prepared customer features and evaluated on the test dataset.

### 4. Model Evaluation

The model achieved the following results:

| Metric | Score |
|---|---:|
| Accuracy | **77.73%** |
| Precision | **57.59%** |
| Recall | **50.37%** |
| F1-Score | **53.74%** |

These metrics help evaluate how effectively the model identifies customers likely to churn.

## 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of customer churn and retention.

### Key KPIs

- **Total Customers:** 7,043
- **Churned Customers:** 1,869
- **Active Customers:** 5,174
- **Churn Rate:** 26.54%
- **Retention Rate:** 73.46%
- **Average Monthly Charges:** $64.76
- **Average Tenure:** 32 months

### Dashboard Analysis

The dashboard analyzes churn across different customer characteristics, including:

- Gender
- Senior Citizen status
- Paperless Billing
- Internet Service
- Customer churn status

![Customer Churn Dashboard](screenshots/customer_churn_dashboard.png.png)
## 💡 Key Insights

- The dataset contains **7,043 customers**, with **1,869 customers classified as churned**.
- The overall churn rate is **26.54%**.
- The majority of customers remain active, with a retention rate of **73.46%**.
- Customer tenure, service type, billing preferences, and customer characteristics can be analyzed to understand churn behavior.
- The ANN model provides a machine-learning approach for identifying customers who may be at risk of churn.

## 📁 Repository Structure

```text
customer-churn-analysis/
│
├── data/
│   └── TelecomCustomerChurn.csv
│
├── python/
│   └── customer_churn_prediction.ipynb
│
├── powerbi/
│   └── customer_churn_dashboard.pbix
│
├── screenshots/
│   └── customer_churn_dashboard.png
│
└── README.md
