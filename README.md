📊 HR Attrition Analysis Dashboard (Power BI)
🔷 Project Overview

This project focuses on analyzing employee attrition patterns using Power BI. The goal is to identify key factors driving employee turnover and provide actionable insights to improve employee retention.

The dashboard is built using a dataset of 1470 employees, covering demographics, job roles, salary, satisfaction levels, and work conditions.

🎯 Objectives
Understand why employees leave the organization
Identify high-risk employee groups
Analyze impact of salary, overtime, satisfaction, and tenure
Enable data-driven HR decisions
📁 Dataset Information

The dataset includes the following key features:

Demographics: Age, Gender, Marital Status
Job Details: Department, Job Role, Job Level
Compensation: Monthly Income, Salary Hike
Work Factors: OverTime, Business Travel, Distance from Home
Satisfaction Metrics: Job Satisfaction, Work-Life Balance, Environment Satisfaction
Experience: Total Working Years, Years at Company, Years Since Last Promotion

📌 Key KPIs
👥 Total Employees: 1470
🚪 Total Attrition: 237
📉 Attrition Rate: 16.1%
💰 Average Salary
⏳ Average Tenure
📊 Dashboard Features

🔹 Overview Page
KPI Cards (Employees, Attrition, Attrition Rate)
Attrition by Department
Attrition by Gender

🔹 Employee Analysis
Attrition by Age Group
Attrition by Tenure Group
Attrition by Job Role

🔹 Work Factors Analysis
Attrition vs OverTime
Attrition vs Work-Life Balance
Attrition vs Job Satisfaction

🔹 Interactive Filters (Slicers)
Department
Job Role
Gender
Marital Status
Attrition
Age Group
Salary Band

🧮 DAX Measures Used

Total Employees = COUNT(HR[EmployeeNumber])

Total Attrition = SUM(HR[Attrition Flag])

Attrition Rate = 
DIVIDE([Total Attrition], [Total Employees])

Avg Salary = AVERAGE(HR[MonthlyIncome])

Avg Tenure = AVERAGE(HR[YearsAtCompany])

🧠 Key Insights
⚠️ Employees working overtime are more likely to leave
📊 Sales department has higher attrition compared to others
👥 Majority of attrition occurs in 25–35 age group
💸 Lower salary employees show higher attrition
📉 Employees with low job satisfaction tend to leave more

💡 Recommendations
Improve work-life balance by reducing overtime
Focus on early-career employee engagement
Review salary structure for lower bands
Enhance career growth & promotion opportunities
Implement employee satisfaction programs

🛠 Tools & Technologies
Power BI
DAX (Data Analysis Expressions)
Data Modeling
Data Visualization

🚀 How to Use
Download the .pbix file from the repository
Open in Power BI Desktop
Use slicers to explore insights dynamically
📷 Dashboard Preview

(Add your dashboard screenshot here)

📌 Project Learnings
Building end-to-end dashboards
Writing optimized DAX measures
Creating business-driven insights
Improving data storytelling
🔗 Connect With Me

If you liked this project, feel free to connect and share your feedback!
