HR Analytics Dashboard

![HR Dashboard](HR_Dashboard.png)

Project Overview

This project analyzes employee data using Power BI to uncover insights related to workforce trends, employee attrition, job satisfaction, and workforce demographics.

The dashboard helps HR teams monitor attrition patterns, understand workforce distribution, and identify factors affecting employee retention.

Key KPIs

Overall Employees: 1470

Attrition Count: 237

Attrition Rate: 16.12%

Active Employees: 1233

Average Age: 37

DAX Measures Used
Active Employees = 
SUM('HR data'[Employee Count]) - SUM('HR data'[Attrition Count])

Attrition Rate = 
DIVIDE(SUM('HR data'[Attrition Count]), SUM('HR data'[Employee Count]))
Dashboard Analysis
1. Workforce Overview

Displays the total number of employees in the organization.

Highlights employee attrition and currently active employees.

Shows the overall workforce age average.

2. Department-wise Attrition

Attrition is analyzed across departments:

R&D

Sales

HR

Helps identify departments with higher employee turnover.

3. Age Group Distribution

Employee distribution across age groups:

Under 25

25–34

35–44

45–54

Over 55

Gender distribution is also visualized within each age group.

4. Job Satisfaction Analysis

Job satisfaction ratings from 1 to 4 are analyzed for different job roles.

Helps identify which roles have higher or lower satisfaction levels.

5. Education Field Attrition

Attrition is analyzed based on employee education background:

Life Sciences

Medical

Marketing

Technical Degree

Human Resources

Other

This helps identify which educational fields experience higher employee turnover.

6. Gender-wise Attrition by Age Group

Displays attrition trends across different age groups for male and female employees.

Helps understand demographic patterns affecting attrition.

Key Features

Interactive slicers for Education Degree levels

Department-wise attrition visualization

Gender and age-based workforce insights

Job satisfaction heatmap

Clear KPI cards for quick HR insights

Tools & Technologies

Power BI

Power Query

DAX

Data Modeling

Files Included

HR_Analytics_Dashboard.pbix

HR_Dashboard.png
