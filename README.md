# 🏦 Bank Customer Churn Prediction

A machine learning project designed to predict bank customer churn. By identifying customers who are likely to leave the bank, financial institutions can take proactive retention measures to reduce customer attrition.

---

## 🎯 Project Overview

Customer churn is a critical metric for banks. Acquiring new customers is significantly more expensive than retaining existing ones. This project builds a predictive model to flag high-risk customers based on features such as demographic details, account balance, credit score, product usage, and activity status.

---

## 📊 Dataset

- **Features typically include:**
  - *CreditScore*: Customer's credit score
  - *Geography*: Customer's country (e.g., France, Spain, Germany)
  - *Gender*: Male / Female
  - *Age*: Age of the customer
  - *Tenure*: Number of years the customer has been with the bank
  - *Balance*: Account balance
  - *NumOfProducts*: Number of bank products the customer uses
  - *HasCrCard*: Whether the customer has a credit card (0 or 1)
  - *IsActiveMember*: Active membership status (0 or 1)
  - *EstimatedSalary*: Estimated salary of the customer

- **Target Variable:**
  - *Exited*: Indicates whether the customer churned (1) or stayed (0)

---

## ⚙️ Tech Stack

- **Language:** Python
- **Libraries:**
  - Data Manipulation & Analysis: `Pandas`, `NumPy`
  - Data Visualization: `Matplotlib`, `Seaborn`
  - Machine Learning: `Scikit-Learn`

---

## 🔄 Project Workflow

1. **Data Preprocessing & Cleaning:**
   - Handling missing values and formatting data types.
   - Encoding categorical variables such as *Geography* and *Gender*.
   - Feature scaling and normalization.

2. **Exploratory Data Analysis (EDA):**
   - Visualizing feature distributions and correlations with churn.
   - Analyzing class balance in the target variable (`Exited`).

3. **Model Training & Evaluation:**
   - Splitting data into training and testing sets.
   - Training machine learning models such as Logistic Regression, Random Forest, and Decision Trees.
   - Evaluating models using metrics like **Accuracy, Precision, Recall, F1-Score, and ROC-AUC**.

---

## 🚀 Installation & Usage

### 1. Clone the repository

    git clone https://github.com/Tabassumasra05/Bank_Customer_Churn_Prediction.git
    cd Bank_Customer_Churn_Prediction

### 2. Install dependencies

    pip install -r requirements.txt

### 3. Run the project

Open the Jupyter Notebook or Python script to view the data analysis, model training, and customer churn predictions.

---
