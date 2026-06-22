# 👨‍💼 HR Workforce Analytics Dashboard | Power BI Project

<div align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-25%2B%20Measures-blue?style=for-the-badge)
![HR Analytics](https://img.shields.io/badge/Domain-HR%20Analytics-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

### 📊 Employee / HR Dataset All In One Analytics Solution

Transforming raw HR data into actionable workforce insights using Power BI, DAX, Data Modeling, and Time Intelligence.

</div>

---

# 🚀 Project Overview

This project was developed as part of the **Power BI Practical Report 4 (PR-4)**.

The dashboard provides a comprehensive analysis of:

* 👥 Workforce Overview
* 📉 Employee Attrition Analysis
* 💰 Compensation & Training Analytics
* 📈 Performance Insights
* 🎯 Recruitment & Hiring Trends
* 📚 Training Investment Analysis

The solution combines multiple datasets into a centralized analytical model using relationships, calculated columns, measures, and advanced DAX functions.

---

# 🗂️ Dataset Information

The project uses the **Employee / HR Dataset All in One** dataset containing:

| Dataset                             | Description                                    |
| ----------------------------------- | ---------------------------------------------- |
| employee_data.csv                   | Employee demographics & employment information |
| recruitment_data.csv                | Recruitment & hiring details                   |
| performance_data.csv                | Employee performance records                   |
| employee_engagement_survey_data.csv | Employee engagement & satisfaction             |
| training_and_development_data.csv   | Training programs & costs                      |

### Dataset Highlights

✅ 50,000+ Records

✅ Multi-table Relational Model

✅ Employee-Centric Analytics

✅ Multi-Year Historical Data

---

# 🏗️ Data Model

The project follows a Star Schema architecture where:

* EmployeeMaster acts as the central fact table.
* Training, Recruitment, Engagement Survey, and Performance tables are connected using Employee ID.
* A custom DimDate table enables Time Intelligence calculations.


## 🔗 Data Model & Query Dependency

![Query Dependency](Screenshots/ss_4.PNG)## 👥 Workforce Overview

![Workforce Overview](Screenshots/ss_1.PNG)

### Key Insights

* Total Employees
* Active Employees
* Average Salary
* Workforce Diversity
* Career Level Distribution
* High Performer Analysis

---

## 📉 Attrition Analysis

![Attrition Analysis](Screenshots/ss_2.PNG)

### Key Insights

* Attrition Rate %
* Employee Turnover
* Hiring Trends
* YTD Attrition Analysis
* Department-wise Attrition

---

## 💰 Compensation & Training Analytics

![Compensation Dashboard](Screenshots/ss_3.PNG)

### Key Insights

* Salary Distribution
* Department Salary Ranking
* Training Investment
* Average Salary by Department
* Performance vs Compensation

---

# 📄 Dashboard Preview PDF

A complete dashboard walkthrough PDF is available inside the repository.

📥 **Dashboard Preview:** `Dashboard_Preview.pdf`

---

# 🧠 DAX Concepts Implemented

### Calculated Columns

* Tenure_Years
* Career_Level_Band
* Full_Name
* Salary_Band
* Is_Active
* Performance_Label
* Salary_Formatted
* Days_Since_Hire
* Hire_Year_Month
* Above_Avg_Salary_Flag

### Measures

#### Workforce Metrics

* Total_Headcount
* Active_Headcount
* Terminated_Count
* Avg_Salary
* Total_Salary_Cost
* Avg_Tenure
* Distinct_Departments
* Avg_Performance_Rating

#### HR KPIs

* Attrition_Rate_%
* Gender_Diversity_Ratio
* Bench_Utilisation_%
* High_Performers_Count
* High_Performer_%

#### Training Metrics

* Avg_Training_Cost
* Total_Training_Cost

#### Advanced DAX

* Total_HC_All_Depts
* Headcount_%_of_Total
* Dept_Avg_Salary_AEXCEPT
* Senior_Headcount
* Salary_Rank_Dept
* Training_Cost_Rank

#### Time Intelligence

* YTD_New_Hires
* New_Hires_SPLY
* New_Hires_YoY_%
* Hires_Prior_3M
* Attrition_Rate_YTD

---

# 📈 Dashboard Pages

| Page                  | Description                              |
| --------------------- | ---------------------------------------- |
| 👥 Workforce Overview | Employee demographics and workforce KPIs |
| 📉 Attrition Analysis | Employee turnover and hiring analysis    |
| 💰 Compensation       | Salary and training investment insights  |

---

# 🛠️ Tools & Technologies

* Microsoft Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Time Intelligence Functions
* Excel / CSV Data Sources

---

# 🎯 Business Outcomes

✔ Workforce visibility

✔ Attrition monitoring

✔ Department performance benchmarking

✔ Salary distribution analysis

✔ Training investment tracking

✔ Strategic HR decision support

---

# 📁 Repository Structure

```text
HR-Analytics-PowerBI/
HR-Workforce-Analytics/
│
├── HR_Workforce_Analytics.pbix
├── HR_Workforce_dashboard_pdf.pdf
├── README.md
│
├── Dataset/
│   ├── employee_data.csv
│   ├── recruitment_data.csv
│   ├── performance_data.csv
│   ├── employee_engagement_survey_data.csv
│   └── training_and_development_data.csv
│
├── screenshort/
│   ├── ss_1.png
│   ├── ss_2.png
│   ├── ss_3.png
│   └── ss_4.png


```

---

# 👨‍💻 About Me

## Meet Mehta

📊 Aspiring Data Analyst
💻 Excel • Power BI • SQL • Python
🚀 Passionate about transforming data into insights

---
<div align="center">

⭐ If you found this project interesting, consider giving it a star!

</div>
