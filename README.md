# IBM HR Analytics - Employee Attrition Analysis

##  Overview
This project focuses on analyzing employee attrition using the IBM HR Analytics dataset. The goal is to identify key factors that influence employee turnover and build a simple machine learning model to predict whether an employee is likely to leave the organization.

---

##  Objectives
- Analyze patterns and trends behind employee attrition  
- Identify key factors affecting employee retention  
- Perform exploratory data analysis (EDA)  
- Build a basic machine learning model for prediction  

---

##  Dataset
- Source: IBM HR Analytics Dataset  
- Records: 1470 employees  
- Features: 35 columns (numerical + categorical)  
- Target Variable: **Attrition (Yes/No)**  

---

##  Exploratory Data Analysis (EDA)
Key insights were derived using visualizations:
- Attrition is higher among younger employees  
- Frequent business travel increases attrition risk  
- Work-life balance plays a major role in retention  
- Certain departments show higher attrition rates  

---

##  Data Preprocessing
- Removed irrelevant columns  
- Encoded categorical variables  
- Feature selection and basic transformation applied  

---

##  Model Building
Implemented simple machine learning models:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors  

✔️ Logistic Regression used for interpretability  
✔️ Random Forest achieved best performance  

---

##  Results & Insights
- Work-life balance, income, and job satisfaction are key drivers  
- Employees with frequent travel and low satisfaction are more likely to leave  
- ML models can effectively predict attrition trends  

---

##  Business Impact
This analysis helps organizations:
- Identify employees at risk of leaving  
- Improve employee engagement strategies  
- Make data-driven HR decisions  

---

##  Future Improvements
- Use advanced models (XGBoost, etc.)  
- Deploy model using Flask/Streamlit  
- Add real-time prediction dashboard  

---

##  Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## 📌 Conclusion
By leveraging data analysis and simple machine learning techniques, this project provides actionable insights into employee attrition. Organizations can use these insights to improve retention strategies and build a more stable workforce.
