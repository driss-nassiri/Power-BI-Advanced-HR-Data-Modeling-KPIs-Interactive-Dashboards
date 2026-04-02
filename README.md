HR ANALYTICS DASHBOARD (POWER BI)

================= 1. PROJECT OVERVIEW
This project aims to analyze
Human Resources (HR) data using Power BI in order to monitor employee
performance, workforce structure, and key HR indicators.

The dashboard provides insights into employee distribution, turnover,
and retention to support data-driven decision-making.

================= 2. OBJECTIVES
======================================== - Analyze employee data
effectively - Build a Star Schema data model - Create dynamic DAX
measures - Design an interactive and professional dashboard

================= 3. DATA PROCESSING STEPS
========================================

3.1 Data Import - Imported CSV files into Power BI - Used Power Query
for data loading

3.2 Data Cleaning - Checked and corrected data types - Handled missing
values - Standardized columns

3.3 Data Modeling - Created a Fact Table: people_fact - Created
Dimension Tables: * Department * Job Level * Education * Location *
Marital Status - Established relationships (Many-to-One) - Built a Star
Schema model

================= 4. DAX MEASURES
========================================

All Employees: Counts unique employees
DISTINCTCOUNT(people_fact[Employee ID])

Headcount: Number of active employees based on hire and termination
dates

Employees Left: Number of employees who left the company

Turnover: Employees Left / Headcount

================= 5. DASHBOARD STRUCTURE
========================================

Page 1: Headcount - KPI: Total Headcount - Distribution by Department
and Job Level - Demographics (Gender, Age, Education) - Geographic
analysis (Map)

Page 2: Retention - Retention KPI - Comparison analysis (min/max) -
Breakdown by Department and Job Level

Page 3: Turnover - Turnover KPI - Employee exit analysis - Termination
reasons - Time-based trends

================= 6. KEY CONCEPTS USED
======================================== - DAX (CALCULATE, FILTER,
DISTINCTCOUNT) - Filter Context - Star Schema - Data Relationships
(Many-to-One)

================= 7. TOOLS USED
======================================== - Power BI - Power Query - DAX

================= 8. CONCLUSION
======================================== This project demonstrates how
raw HR data can be transformed into actionable insights using Power BI
through data modeling, DAX calculations, and interactive visualizations.
