# 📊 Credit Card Transaction Dashboard | Power BI Project

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
