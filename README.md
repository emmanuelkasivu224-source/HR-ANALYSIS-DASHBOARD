<img width="927" height="497" alt="dashboard" src="https://github.com/user-attachments/assets/475445f3-4450-4a58-9eca-f18ad63a3752" />
<img width="1090" height="230" alt="insights" src="https://github.com/user-attachments/assets/f7e5723d-847c-44e3-b428-097f3c7d7948" />
# HR Analysis Dashboard – Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-Analytics-yellow)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-HR-blue)
![Dashboard](https://img.shields.io/badge/Dashboard-Interactive-green)

## Project Overview

The HR Analysis Dashboard is an interactive Human Resources analytics project developed using Microsoft Power BI.

The purpose of the project is to transform employee-related data into an interactive dashboard that enables HR teams, managers, and business decision-makers to monitor workforce trends, employee satisfaction, salary patterns, overtime, departmental performance, education distribution, and employee attrition.

The dashboard provides a centralized view of important HR Key Performance Indicators (KPIs) and visual insights that can support data-driven workforce management and employee retention strategies.

---

## Dashboard Preview

### Main HR Dashboard

![HR Analysis Dashboard](Screenshots/dashboard.jpeg)

### HR Insights & Recommendations

![HR Insights](Screenshots/insights.jpeg)

---

## Business Problem

Human Resources departments often manage large amounts of employee information, including:

- Employee demographics
- Salaries
- Departments
- Education
- Job roles
- Employee satisfaction
- Overtime
- Employee attrition
- Tenure
- Workforce performance

When this information is stored only in spreadsheets or databases, it can be difficult to identify important patterns quickly.

The purpose of this project is to convert raw HR data into an interactive Power BI dashboard that allows decision-makers to quickly identify workforce trends and potential employee retention risks.

---

## Project Objectives

The main objectives of this project are to:

1. Analyze employee attrition.
2. Monitor the total number of employees.
3. Calculate average monthly salary.
4. Analyze employee satisfaction.
5. Investigate the relationship between overtime and attrition.
6. Compare departments based on employee attrition.
7. Analyze monthly income by department.
8. Examine education field distribution.
9. Identify potential employee retention risks.
10. Provide actionable HR recommendations.
11. Present HR data in an interactive and easy-to-understand format.

---

## Key Performance Indicators

The dashboard contains several high-level HR KPIs.

### Total Employees

The dashboard reports:

**500 employees**

This KPI provides an overview of the size of the workforce represented in the dataset.

### Attrition Rate

The dashboard includes an employee attrition rate KPI.

Attrition rate helps HR teams understand the proportion of employees leaving the organization.

### Average Monthly Salary

The dashboard reports an average monthly salary of approximately:

**10.15K**

This KPI provides an overview of employee compensation levels.

### Average Employee Satisfaction

The dashboard reports an average satisfaction score of:

**2.58**

Employee satisfaction can provide an indication of workforce engagement and potential retention challenges.

---

# Dashboard Components

## 1. Monthly Income by Department

This visualization compares monthly employee income across different departments.

Departments represented include:

- Finance
- Sales
- R&D
- Software Engineering
- Marketing
- Human Resources

The visualization helps identify differences in monthly income distribution across departments.

---

## 2. Attrition by Department

This visualization compares employee attrition across departments.

The dashboard provides a department-level view of employee turnover and allows HR decision-makers to identify departments that may require further investigation.

Departments include:

- Finance
- Software Engineering
- Sales
- Marketing
- R&D
- Human Resources

---

## 3. Overtime and Attrition Analysis

The dashboard analyzes the relationship between overtime and employee attrition.

The analysis indicates a strong difference in attrition between employees who regularly work overtime and those who do not.

According to the analysis:

- Employees working regular overtime show an attrition rate of approximately 31.2%.
- Employees who do not work overtime show an attrition rate of approximately 9.1%.
- This represents approximately a 3.4x difference in attrition rate.

This finding suggests that excessive workload and overtime may be associated with employee turnover.

---

## 4. Education Field Distribution

The dashboard provides a breakdown of employees according to their education field.

Education categories include:

- Human Resources
- Medical
- Marketing
- Technical Degree
- Other

This visualization helps HR teams understand the educational composition of the workforce.

---

# Key HR Insights

## Insight 1 – Overtime and Employee Attrition

The analysis indicates a substantial relationship between overtime and employee attrition.

Employees working regular overtime have a significantly higher attrition rate than employees who do not work overtime.

This may indicate:

- Workload pressure
- Employee burnout
- Poor work-life balance
- Insufficient staffing
- Excessive working hours

### Recommendation

HR management should investigate workload distribution and overtime patterns.

Possible actions include:

- Reviewing overtime policies
- Redistributing workloads
- Increasing staffing in high-pressure teams
- Introducing flexible working arrangements
- Monitoring employee burnout indicators
- Conducting employee engagement surveys

---

## Insight 2 – Early Tenure Retention Risk

Employee turnover appears to be concentrated within the early stages of employee tenure.

The analysis highlights the 1–2 year tenure period, particularly within Sales and Software Engineering.

This may indicate challenges involving:

- Employee onboarding
- Career development
- Compensation expectations
- Management support
- Workload
- Career progression

### Recommendation

The organization should introduce structured retention strategies during the first 18 months of employment.

Potential initiatives include:

- Structured onboarding programs
- Mentorship programs
- Career development plans
- Regular employee check-ins
- Performance feedback
- Internal mobility opportunities
- Professional development programs

---

## Insight 3 – Department-Level Attrition

Different departments display different levels of employee attrition.

This suggests that employee turnover should not necessarily be treated as a company-wide problem only.

HR teams should investigate department-specific factors such as:

- Leadership
- Compensation
- Workload
- Job satisfaction
- Career opportunities
- Employee-manager relationships
- Working conditions

---

# Strategic Action Plan

Based on the dashboard analysis, the following actions are recommended:

### 1. Introduce 18-Month Career Progression Plans

Employees should have clearly defined career milestones during their first 18 months.

### 2. Review Overtime

HR should analyze overtime frequency and identify teams where employees consistently work beyond normal hours.

### 3. Improve Work-Life Balance

Flexible working arrangements and workload management can help reduce burnout.

### 4. Strengthen Employee Onboarding

New employees should receive structured support during their first year.

### 5. Improve Career Development

Employees should have access to training, mentorship, and internal career opportunities.

### 6. Conduct Targeted Exit Analysis

Employees leaving the organization should be analyzed by:

- Department
- Job role
- Tenure
- Salary
- Satisfaction
- Overtime
- Education
- Other relevant factors

---

# Technology Stack

The project was developed using:

- Microsoft Power BI
- Power Query
- DAX
- Data Visualization
- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Business Intelligence

---

# Data Preparation

The data preparation process involved transforming raw employee information into a format suitable for analysis.

Typical preparation activities included:

1. Importing the dataset into Power BI.
2. Inspecting columns and data types.
3. Identifying missing values.
4. Cleaning inconsistent values.
5. Transforming data using Power Query.
6. Creating calculated measures.
7. Creating calculated columns where necessary.
8. Building relationships between tables where applicable.
9. Creating an analytical data model.
10. Designing dashboard visualizations.

---

# Power BI Development Process

The project followed a typical data analytics workflow:

Raw Data
   ↓
Data Cleaning
   ↓
Data Transformation
   ↓
Data Modeling
   ↓
DAX Measures
   ↓
Data Analysis
   ↓
Visualization
   ↓
Dashboard
   ↓
Insights & Recommendations

---

# DAX Measures

Example measures used or suitable for this project include:

## Total Employees

```DAX
Total Employees =
COUNTROWS('HR Data')

Avg Monthly Salary =
AVERAGE('HR Data'[MonthlyIncome])

Avg Satisfaction =
AVERAGE('HR Data'[JobSatisfaction])

Attrition Count =
CALCULATE(
    COUNTROWS('HR Data'),
    'HR Data'[Attrition] = "Yes"
)

Attrition Rate =
DIVIDE(
    [Attrition Count],
    [Total Employees],
    0
)


