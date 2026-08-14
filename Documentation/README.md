# HR Analysis Dashboard
## Detailed Project Documentation

---

# 1. Introduction

The HR Analysis Dashboard is a Business Intelligence project developed using Microsoft Power BI.

The project focuses on analyzing employee-related information and transforming raw HR data into meaningful visual insights.

Human Resources departments generate large volumes of workforce data. However, raw data alone does not provide decision-makers with an immediate understanding of employee behavior.

Business Intelligence tools such as Power BI can transform this data into interactive dashboards that allow users to identify trends, compare departments, monitor KPIs, and make informed decisions.

This project demonstrates how HR data can be transformed through a complete analytics workflow:

Raw Data → Cleaning → Transformation → Modeling → Analysis → Visualization → Insights → Recommendations

---

# 2. Project Purpose

The main purpose of the project is to create an interactive HR analytics dashboard capable of providing an executive-level overview of workforce information.

The dashboard focuses on:

- Employee population
- Employee attrition
- Salary
- Employee satisfaction
- Overtime
- Department performance
- Education distribution
- Employee retention

The final dashboard is intended to help decision-makers quickly identify important workforce patterns.

---

# 3. Business Problem

Organizations need to understand why employees leave, which departments experience higher turnover, whether workload is associated with attrition, and whether employee satisfaction may be affecting retention.

Without an analytical dashboard, HR managers may need to manually inspect spreadsheets or reports.

This creates several problems:

- Slow reporting
- Difficulty identifying trends
- Limited interactive analysis
- Difficulty comparing departments
- Limited executive visibility
- Manual calculations
- Delayed decision-making

The dashboard addresses these challenges by consolidating key HR metrics into one interactive analytical interface.

---

# 4. Project Objectives

The project objectives are:

### Objective 1

Develop an interactive HR dashboard using Power BI.

### Objective 2

Create meaningful HR KPIs.

### Objective 3

Analyze employee attrition.

### Objective 4

Compare employee attrition across departments.

### Objective 5

Investigate overtime and attrition.

### Objective 6

Analyze employee salary levels.

### Objective 7

Analyze employee satisfaction.

### Objective 8

Analyze education-field distribution.

### Objective 9

Identify possible employee retention risks.

### Objective 10

Provide actionable recommendations based on the analysis.

---

# 5. Tools and Technologies

## Microsoft Power BI

Power BI was used to:

- Import data
- Clean data
- Transform data
- Model data
- Create measures
- Create visualizations
- Build the dashboard
- Generate analytical insights

## Power Query

Power Query was used for data preparation and transformation.

Typical activities included:

- Removing unnecessary columns
- Changing data types
- Renaming columns
- Handling missing values
- Filtering records
- Creating transformed fields
- Preparing data for analysis

## DAX

DAX was used to create analytical measures.

Examples include:

- Total Employees
- Attrition Count
- Attrition Rate
- Average Monthly Salary
- Average Satisfaction

---

# 6. Dataset

The dashboard uses employee-related HR information.

Important fields used for analysis include categories such as:

- Department
- Gender
- Attrition
- Overtime
- Monthly Income
- Job Satisfaction
- Education Field
- Years at Company
- Employee Tenure

The exact columns depend on the source dataset used to create the report.

---

# 7. Data Preparation

Data preparation is an important stage of the project.

The process begins by importing the source dataset into Power BI.

After importing the data, the dataset is inspected for:

- Missing values
- Incorrect data types
- Duplicate records
- Inconsistent categories
- Unnecessary fields
- Invalid values

The data is then transformed using Power Query.

---

# 8. Data Transformation

The transformation stage prepares the raw data for analysis.

Typical transformations include:

### Data Type Conversion

Numeric columns are converted to appropriate numeric data types.

Categorical columns are converted to text.

### Column Cleaning

Unnecessary columns are removed.

### Category Standardization

Categories are standardized so that similar values are not treated as different categories.

### Missing Data

Missing values are investigated and handled appropriately.

---

# 9. Data Modeling

The cleaned data is prepared for Power BI analysis.

The data model allows the dashboard to calculate metrics dynamically based on filters.

A good data model is important because it ensures that visualizations return meaningful results.

---

# 10. Key Performance Indicators

The dashboard contains four main KPI cards.

## Total Employees

Displays the number of employees represented in the analysis.

Displayed dashboard value:

**500**

---

## Attrition Rate

Measures the proportion of employees who have left the organization.

Conceptually:

```text
Attrition Rate =
Employees who left / Total Employees
