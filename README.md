# SmartaCorp Analysis

![](HR.jpg)

## Introduction
**SmartaCorp** is a fast-growing mid-sized company in the technology sector with over 200 active employees across various departments.
The report covers the data modeling, DAX measures, visualization choices, insights, and recommendations for improvement. Smartacorp’s Human Resources data reveals a mature, experienced, and leadership-heavy workforce. With 207 active employees, the company boasts an average tenure of 9years, and 100% of active staff have over 5 years of experience which is a clear indicator of a highly tenured and stable workforce.
## Objective
The dashboard aims to address key HR questions related to workforce composition, salary insights, experience overview, and diversity and inclusion at SmartaCorp.
## Tool used
PowerBI 
## Data Transformation
The dataset was cleaned by removing duplicates and missing values, standardization of categorical field and calculated derived metrics using DAX.
## Data Modeling
A star schema with ‘HRDataset’ as the fact table linked to dimension tables such as Gender, Marital status, Position, EmployeeInfo and EmployStatus was created. One-to-Many relationship was established between the fact table and dimensions to enable filtering and slicing.
## SmartaCorp Dashboard 
The dashboard provides an interactive overview of SmartaCorp's workforce, focusing on:
Workforce Composition (Employee count, gender distribution and department headcount)
Salary Insights (Average salary, salary differences by department and gender, and highest-paying departments).
Experience Overview (Average years of service, employees with 5+ years of tenure, and departments with the most experienced staff).
Diversity and Inclusion (Gender imbalance across departments and representation of women in leadership/technical roles).
## Visualization Analysis
KPI Cards: Total number employees (311), Number of active employes (207), Avg. Years of Service (9years) indicating high employee retention and Avg. Monthly Salary ($5.75K).
Pie chart and bar chart shows gender distribution by total number of employees and department which is 155 Female and 176 Male.
Stacked bar chart (Salary by Department and Gender) reveals disparities such as Production has the highest salary sum but a gender imbalance (59.95% Female contribution).
Table (Department by Role and Gender) highlights gender representation in roles (e.g., Technical vs. Leadership). Women are underrepresented in Leadership (Executive Office).
Bar chart (Year of Service by Department) shows departments like Executive Office have the most experienced staff (avg. 11 years).
## Insights
Gender Imbalance: The Production department has a significant female majority (126 employees), while Leadership roles (Executive Office) are male-dominated.
High Retention but Potential Stagnation: Average tenure is 9 years, suggesting strong retention but possible stagnation in career growth.
Salary Disparities: The Executive Office has the highest average salary, but gender representation is skewed.
## Recommendations
Addressing the burnouts by supporting high tenured teams. All active employees have 5+ years of experience, indicating a very tenured workforce (group of employees who have been with the organization for a long period of time).
Prioritizing diversity in hiring especially in the male and female dominated teams. Based on gender imbalance, the production team needs to have more of the male counterpart employed to have a balance in the department and have more employees in the executive positions occupied as well.
Under the status on voluntarily terminated, it is observed that the production had the highest count with 75 individuals and based on the average yearly salary it also shows that production department is the second lowest earning department; having their pay increased will have reduced turnover and enthusiasm to be improved.
## Conclusion
The HR Insights dashboard effectively addresses SmartaCorp's key questions but has room for improvement in clarity and completeness. Implementing the recommendations will enhance its value for data-driven HR strategies. The DAX and data modeling provide a solid foundation for future iterations.
