# Telco Customer Churn Analysis using Python

Exploratory Data Analysis (EDA) of telecom customer data using Python to identify key factors influencing customer churn and provide actionable business insights.

---

## 📌 Project Overview

This project performs in-depth Exploratory Data Analysis on a telecom customer dataset to understand customer behavior and identify patterns that lead to churn.

The analysis helps identify:

* High-risk customers likely to churn
* Impact of contract type on churn
* Customer behavior based on demographics
* Service-related factors affecting retention

---

## 🛠️ Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📁 Dataset

The dataset contains telecom customer information including:

* Customer demographics (Gender, Senior Citizen, Dependents)
* Account information (Tenure, Contract Type, Payment Method)
* Services used (Internet Service, Streaming, Tech Support)
* Billing details (Monthly Charges, Total Charges)
* Target variable: **Churn (Yes/No)**

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Handled missing values in **TotalCharges**
* Converted data types for accurate analysis
* Transformed categorical variables
* Standardized inconsistent values (e.g., SeniorCitizen)

---

## 📊 Exploratory Data Analysis

### 🔹 Churn Distribution

Analyzed overall churn rate in the dataset.

**Key Insight:** Around 25–30% of customers have churned, indicating a significant retention challenge.
<img width="710" height="374" alt="image" src="https://github.com/user-attachments/assets/77678ca2-fc3c-4c47-9e81-5201a3cf6e9d" />


---

### 🔹 Gender Analysis

Analyzed churn behavior based on gender.

**Key Insight:** No major difference in churn between male and female customers.
<img width="695" height="400" alt="image" src="https://github.com/user-attachments/assets/da983535-9516-4f30-8f7f-466fe9a7090b" />


---

### 🔹 Senior Citizen Analysis

Compared churn rates for senior vs non-senior customers.

**Key Insight:** Senior citizens show a higher churn rate.


---

### 🔹 Tenure Analysis

Analyzed how long customers stay with the company.

**Key Insight:** Customers with shorter tenure are more likely to churn.
<img width="711" height="290" alt="image" src="https://github.com/user-attachments/assets/0cfc0520-9a2e-4623-8343-e444831d0473" />


---

### 🔹 Contract Type Analysis

Studied the impact of contract type on churn.

**Key Insight:**

* Month-to-month customers have the highest churn
* Long-term contracts (1 year, 2 year) reduce churn significantly
  <img width="687" height="414" alt="image" src="https://github.com/user-attachments/assets/c3e3e041-1a4f-4dc9-89a3-7c2a1e9d9ac9" />


---

### 🔹 Services Analysis

Analyzed impact of additional services:

* Online Security
* Tech Support
* Streaming Services

**Key Insight:** Customers without support or security services are more likely to churn.
<img width="301" height="302" alt="image" src="https://github.com/user-attachments/assets/f528ad0f-bbb1-40f8-9901-82ffb277062e" />


---

### 🔹 Payment Method Analysis

Analyzed churn based on payment method.

**Key Insight:** Customers using **electronic check** show higher churn compared to other methods.
<img width="733" height="371" alt="image" src="https://github.com/user-attachments/assets/8772a790-7616-496a-ab73-e824d67c90e8" />


---

## 📈 Key Business Insights

* Customers on **month-to-month contracts** are high-risk
* **Short tenure customers** are more likely to leave
* Lack of **value-added services** increases churn probability
* **Electronic payment users** show higher churn behavior

---

## 🚀 Conclusion

This analysis helps telecom companies:

* Identify high-risk customers
* Improve retention strategies
* Promote long-term contracts
* Enhance service offerings to reduce churn

---

## 👩‍💻 Author

**Poulomee Manna**
