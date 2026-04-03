📊 HR Analytics Dashboard – Power BI
🧾 Project Overview

This project focuses on analyzing Human Resources (HR) data using Power BI.
The objective is to monitor:

Employee performance
Workforce structure
Key HR metrics

The dashboard provides actionable insights into:

📊 Employee distribution
🔄 Turnover
📈 Retention

➡️ Supporting data-driven decision-making.

🎯 Objectives

The main goals of this project are:

📊 Analyze employee data effectively
🏗️ Build a Star Schema data model
🧮 Create dynamic DAX measures
🎨 Design an interactive and professional dashboard
⚙️ Data Processing Steps
📥 1. Data Import
Imported CSV files into Power BI
Used Power Query for data loading
🧹 2. Data Cleaning
Checked and corrected data types
Handled missing values
Standardized columns
🏗️ 3. Data Modeling
Created Fact Table: people_fact
Created Dimension Tables:
Department
Job Level
Education
Location
Marital Status
Established relationships (Many-to-One)
Built a Star Schema model
🧮 DAX Measures
👥 All Employees

Counts the number of unique employees:

DISTINCTCOUNT(people_fact[Employee ID])
📊 Headcount

Number of active employees based on hire and termination dates.

🚪 Employees Left

Number of employees who left the company.

🔄 Turnover
Employees Left / Headcount
📊 Dashboard Structure
📄 Page 1: Headcount
KPI: Total Headcount
Distribution by Department & Job Level
Demographics:
Gender
Age
Education
🌍 Geographic analysis (Map)
📄 Page 2: Retention
📈 Retention KPI
📊 Min/Max comparison
Breakdown by:
Department
Job Level
📄 Page 3: Turnover
🔄 Turnover KPI
Employee exit analysis
📉 Termination reasons
⏳ Time-based trends
🧠 Key Concepts Used
🧮 DAX (CALCULATE, FILTER, DISTINCTCOUNT)
🔍 Filter Context
⭐ Star Schema
🔗 Data Relationships (Many-to-One)
🛠️ Tools Used
📊 Power BI
🔄 Power Query
🧮 DAX
✅ Conclusion

This project demonstrates how raw HR data can be transformed into clear, interactive, and actionable insights using Power BI.

It highlights the importance of:

Data modeling
DAX calculations
Dashboard design

➡️ Delivering valuable insights for HR decision-making.
