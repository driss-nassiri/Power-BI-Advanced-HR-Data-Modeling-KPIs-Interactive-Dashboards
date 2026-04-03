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

### Headcount
Number of active employees based on hire and termination dates.

### Employees Left
Number of employees who left the company.

### Turnover


---

## 📊 Dashboard Structure

### Page 1: Headcount
- KPI: Total Headcount  
- Distribution by Department and Job Level  
- Demographics (Gender, Age, Education)  
- Geographic analysis (Map)  

### Page 2: Retention
- Retention KPI  
- Min/Max comparison  
- Breakdown by Department and Job Level  

### Page 3: Turnover
- Turnover KPI  
- Employee exit analysis  
- Termination reasons  
- Time-based trends  

---

## 🧠 Key Concepts Used
- DAX (CALCULATE, FILTER, DISTINCTCOUNT)  
- Filter Context  
- Star Schema  
- Data Relationships (Many-to-One)  

---

## 🛠️ Tools Used
- Power BI  
- Power Query  
- DAX  

---

## ✅ Conclusion
This project demonstrates how raw HR data can be transformed into actionable insights using Power BI.

It highlights:
- Data modeling  
- DAX calculations  
- Interactive dashboards  
