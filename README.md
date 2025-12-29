<!-- Header Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6a11cb,100:2575fc&height=180&section=header&text=💳%20Credit%20Card%20Transaction%20Dashboard&fontSize=36&fontColor=ffffff&animation=fadeIn&fontAlignY=35"/>
</p>

## 📌 Project Overview

The **Credit Card Transaction Dashboard** is a **Business Intelligence project built using Power BI, SQL, and DAX** to analyze **financial performance, customer behavior, and transaction trends** from credit card data.

This dashboard provides **real-time, interactive insights** that help stakeholders monitor revenue, transactions, customer segments, and operational metrics for data-driven decision-making.

---

## 🎯 Project Objective

- Build an **interactive Power BI dashboard** for credit card transactions  
- Deliver **real-time insights** into:
  - Revenue & interest
  - Transaction amount & count
  - Customer demographics
  - Card & usage patterns
- Enable **weekly, quarterly, and YTD performance analysis**

---

## 🗂️ Data Source

- Data stored and managed in a **SQL Database**
- Imported from CSV files into SQL tables
- Two primary tables:
  - `cc_details` – Credit card transaction data
  - `cust_details` – Customer demographic data

🔗 **GitHub Repository:**  
https://github.com/shivareddy2002/Credit_Card_Transaction_Report

---

## 🛠️ Tech Stack & Tools Used

- **Power BI** – Dashboard development & visualization  
- **SQL (MySQL / PostgreSQL)** – Data storage & querying  
- **DAX** – Measures, KPIs & time intelligence  
- **Data Modeling** – Relationships & schema design  
- **Data Visualization** – KPIs, charts, slicers  

---

## 🧱 Database Schema

### 1️⃣ Credit Card Details Table (`cc_details`)

```sql
CREATE TABLE cc_details (
    Client_Num INT,
    Card_Category VARCHAR(20),
    Annual_Fees INT,
    Activation_30_Days INT,
    Customer_Acq_Cost INT,
    Week_Start_Date DATE,
    Week_Num VARCHAR(20),
    Qtr VARCHAR(10),
    current_year INT,
    Credit_Limit DECIMAL(10,2),
    Total_Revolving_Bal INT,
    Total_Trans_Amt INT,
    Total_Trans_Ct INT,
    Avg_Utilization_Ratio DECIMAL(10,3),
    Use_Chip VARCHAR(10),
    Exp_Type VARCHAR(30),
    Interest_Earner DECIMAL(10,3),
    Delinquent_Acc VARCHAR(5)
);

```

### 🔹 Customer Details Table (`cust_details`)

```sql
CREATE TABLE cust_details (
    Client_Num INT,
    Customer_Age INT,
    Gender VARCHAR(10),
    Dependent_Count INT,
    Education_Level VARCHAR(50),
    Maritial_Status VARCHAR(20),
    State_cd VARCHAR(50),
    Zipcode VARCHAR(20),
    car_Owner VARCHAR(10),
    House_Owner VARCHAR(5),
    Personal_Loan VARCHAR(5),
    Contact VARCHAR(20),
    Customer_Job VARCHAR(20),
    Income INT,
    Customer_Satisfaction_Score INT
);
```
## 📊 Dashboard Features

### 🔹 Key KPIs
- 💰 **Total Revenue**
- 💳 **Total Transaction Amount**
- 🔢 **Transaction Count**
- 💸 **Interest Earned**
- 👥 **Customer Count**
- ⚠️ **Delinquency Rate**
- ✅ **Activation Rate**

---

### 🔹 Interactive Analysis
The dashboard includes dynamic filters for:
- **Quarter**
- **Card Category**
- **Gender**
- **Income Group**
- **Education Level**
- **Transaction Type** (Swipe / Chip / Online)

---

## 📈 Key Insights
- 💰 **Total Revenue:** 55M  
- 💳 **Blue & Silver cards** contribute ~93% of total transactions  
- 🔄 **Swipe transactions** dominate overall usage  
- 👥 Significant variation across **age, income, and job groups**  
- 🌎 **TX, NY & CA** together contribute ~68% of total revenue  
- ⚠️ **Delinquent Rate:** 6.06%  
- ✅ **Activation Rate:** 57.5%  

---

## 📤 Export & Sharing
Dashboard outputs were shared as:
- **PDF reports**
- **Power BI Service dashboards**

Used for:
- **Weekly performance reviews**
- **Business & strategic discussions**

---

## 🚀 Future Enhancements
- Predictive analytics for:
  - **Revenue forecasting**
  - **Delinquency prediction**
- **Automated data refresh** using Power BI Service
- **Drill-through customer-level analysis**
- Integration with **Machine Learning models**

---

## 👨‍💻 Author
**Lomada Siva Gangi Reddy**  
🎓 B.Tech CSE (Data Science), RGMCET (2021–2025)  
🎯 Aspiring Data Analyst  

📞 **Phone:** 9346493592  

🔗 **LinkedIn:**  
https://www.linkedin.com/in/lomada-siva-gangi-reddy-a64197280/  

💻 **GitHub:**  
https://github.com/shivareddy2002  

🌐 **Portfolio:**  
https://lsgr-portfolio-pulse.lovable.app/
