# 🚀 Machine Learning Projects Using Random Forest Classifier – End-to-End Use Cases

This repository contains **end-to-end Machine Learning projects** demonstrating strong fundamentals in **EDA, feature engineering, model building, evaluation, and business impact analysis** using Python.

Each project follows the **Machine Learning Life Cycle** and is documented with clear objectives, insights, and outcomes.

---

## 📌 Project 1: Customer Purchase Prediction using Random Forest
*(Company Data Analysis)*

### 🎯 Objective
To predict whether a customer is likely to **make a purchase** based on demographic and behavioral attributes, enabling businesses to improve targeting and marketing strategies.

---

### 🧠 Problem Statement
Businesses often struggle to identify customers who are most likely to convert. An automated predictive model helps optimize marketing spend and improve conversion rates by targeting high-probability customers.

---

### 🛠️ Solution Approach
- Performed **Exploratory Data Analysis (EDA)** to understand customer behavior
- Applied **feature encoding and preprocessing**
- Built  **Random Forest classification model  to predict purchase likelihood**
- Evaluated model using appropriate performance metrics

---

### 📊 Key Insights
- Age and salary significantly influence purchase decisions
- Certain demographic segments show higher conversion probability
- Model helps in identifying high-value customers effectively

---

### 💼 Business Impact
- Improved marketing efficiency
- Better customer segmentation
- Data-driven decision making for campaigns
- Reduced customer acquisition cost

---

### 🧰 Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📌 Project 2: Fraud Risk Detection using Random Forest  
*(Fraud Check Analysis)*

### 🎯 Objective
To classify individuals as **“Risky”** or **“Good”** based on financial and demographic attributes using a **Random Forest Classifier**.

**Business Rule Applied:**
- Taxable Income ≤ 30000 → **Risky**
- Taxable Income > 30000 → **Good**

---

### 🧠 Problem Statement
Manual fraud detection is inefficient and prone to errors. Organizations require a scalable and automated system to identify high-risk individuals early to reduce financial losses.

---

### 🛠️ Solution Approach
- Created target variable using domain-specific business rules
- Conducted **separate EDA notebook** with detailed visual analysis
- Encoded categorical variables
- Built and evaluated a **Random Forest classification model**
- Analyzed feature importance for interpretability

---

### 📊 Key Insights
- Taxable income is the strongest indicator of fraud risk
- Lower work experience correlates with higher risk
- City population and demographic attributes also influence risk
- Random Forest handled non-linear relationships effectively

---

### 💼 Business Impact
- Early detection of high-risk individuals
- Reduction in fraud-related financial losses
- Improved compliance and monitoring
- Scalable and automated fraud screening solution

---

### 🧰 Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn (Random Forest)  
- Jupyter Notebook  

---

## 📂 Repository Structure
```text
├── company_data_prj_9.ipynb        # Customer Purchase Prediction Project
├── fraud_check_prj_10.ipynb        # Fraud Risk Detection Project
├── README.md                       # Project documentation
