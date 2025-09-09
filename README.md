# 💳 Credit Card Case Study

## 📌 Objective
The goal of this project is to analyze **customer acquisition, spending, and repayment behavior** to help the bank identify profitable customer segments and calculate monthly profits.

---

## 📂 Dataset
- **Customer Acquisition** – Customer details such as Customer ID, City, Age, etc.  
- **Spend Data** – Monthly spending data by customers.  
- **Repayment Data** – Repayment behavior of customers.  

---

## 🛠️ Steps Performed
1. **Data Cleaning**
   - Replaced ages `< 18` with mean age.  
   - Adjusted spend values greater than credit limits.  
   - Replaced repayments exceeding credit limits with the actual limit.  

2. **Exploratory Data Analysis (EDA)**
   - Calculated distinct customers and product categories.  
   - Measured average monthly spend and repayment amounts.  
   - Identified **top 5 product types** by spending.  
   - Found the **city with maximum spend**.  

3. **Profit Calculation**
   - Applied **2.9% monthly interest** on (spend – repayment).  
   - Estimated **bank profits per month**.  

---

## 📈 Outcome
- Clear insights into **customer spending vs. repayment behavior**.  
- Identified **high-spending product categories and cities**.  
- Estimated **bank profit trends** using interest on repayments.  
- Highlighted customers with **high spending but low repayment rates** for risk management.  

---

## 🛠️ Tech Stack
- **Python** – Pandas, NumPy, Matplotlib  
- **Jupyter Notebook** – Analysis & visualization  
- **Data Cleaning & EDA** techniques  

---

## 📎 Dataset
PIMA Indians dataset (provided during case study).  
*(If public dataset not available, mention "Dataset proprietary – provided by training program")*  

---

✍️ **Author:** Bhaskar Babu  
📌 *Certified Data Science Professional (IIT Guwahati)*  
