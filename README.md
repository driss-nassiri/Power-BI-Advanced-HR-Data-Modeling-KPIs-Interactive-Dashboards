# 📊 HR Analytics Dashboard – Power BI

## 🧾 Project Overview
This project focuses on analyzing **Human Resources (HR) data** using **Power BI**.

The goal is to monitor:
- Employee performance
- Workforce structure
- Key HR metrics

The dashboard provides insights into:
- Employee distribution
- Turnover
- Retention

➡️ Supporting data-driven decision-making.

---

## 🎯 Objectives
- Analyze employee data effectively  
- Build a Star Schema data model  
- Create dynamic DAX measures  
- Design an interactive and professional dashboard  

---

## ⚙️ Data Processing Steps

### 📥 Data Import
- Imported CSV files into Power BI  
- Used Power Query for data loading  

### 🧹 Data Cleaning
- Checked and corrected data types  
- Handled missing values  
- Standardized columns  

### 🏗️ Data Modeling
- Created Fact Table: `people_fact`  
- Created Dimension Tables:
  - Department  
  - Job Level  
  - Education  
  - Location  
  - Marital Status  

- Established relationships (Many-to-One)  
- Built a Star Schema model  

---

## 🧮 DAX Measures

### All Employees
Counts unique employees:
