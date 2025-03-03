# HR Data Analysis

## Overview
This project analyzes HR data containing over 22,000 records from the years 2000 to 2020. The data was cleaned and processed using MySQL Workbench, and insights were visualized using Power BI.

## Data Sources
- **Data:** HR records (2000-2020) with over 22,000 rows.
- **Data Cleaning & Analysis:** MySQL Workbench
- **Data Visualization:** Power BI

## Key Analysis Questions
1. What is the gender breakdown of employees in the company?
2. What is the race/ethnicity breakdown of employees in the company?
3. What is the age distribution of employees in the company?
4. How many employees work at headquarters versus remote locations?
5. What is the average length of employment for employees who have been terminated?
6. How does the gender distribution vary across departments and job titles?
7. What is the distribution of job titles across the company?
8. Which department has the highest turnover rate?
9. What is the distribution of employees across locations by state?
10. How has the company's employee count changed over time based on hire and termination dates?
11. What is the tenure distribution for each department?

## Summary of Findings
- **Gender Breakdown:** There are more male employees than female employees.
- **Race/Ethnicity Breakdown:** The most dominant race is White, while Native Hawaiian and American Indian are the least represented.
- **Age Distribution:**
  - The youngest employee is 20 years old, and the oldest is 57 years old.
  - Employees were grouped into five age categories: 18-24, 25-34, 35-44, 45-54, and 55-64.
  - The largest group is 25-34, followed by 35-44, while the smallest group is 55-64.
- **Work Location:** A large number of employees work at the headquarters compared to remote locations.
- **Employment Duration:** The average length of employment for terminated employees is approximately **7 years**.
- **Gender Distribution Across Departments:** While fairly balanced, the overall trend shows more male employees than female employees.
- **Job Title Distribution:** Job titles are well spread across the company with variations across departments.
- **Turnover Rate by Department:**
  - **Highest Turnover:** Marketing (highest), followed by Training.
  - **Lowest Turnover:** Research & Development, Support, and Legal departments.
- **Employee Distribution by State:** The highest number of employees come from **Ohio**.
- **Employee Count Over Time:** The net change in employee count has increased over the years.
- **Tenure Distribution by Department:**
  - The average tenure is **8 years**.
  - **Highest Tenure:** Legal and Auditing departments.
  - **Lowest Tenure:** Services, Sales, and Marketing departments.

## Limitations
- **Data Issues:**
  - Some records contained negative ages (967 records). These were excluded, keeping only ages 18 and above.
  - Some termination dates were unrealistically far into the future (1,599 records). Only termination dates up to the current date were considered.

## Tools Used
- **SQL Queries:** Data Cleaning and Transformation (MySQL Workbench)
- **Power BI:** Data Visualization

## Conclusion
This analysis provides key insights into the company's workforce distribution, turnover rates, and employee tenure. The findings can help HR departments make data-driven decisions to improve retention and workforce planning.

