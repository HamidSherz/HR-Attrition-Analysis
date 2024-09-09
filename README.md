# HR Attrition Analysis
![HR Attrition Analysis](Intro_image.jpg)

## Overview
This HR analytics dashboard analyzes company-wide attrition rates to identify key drivers and trends, focusing on departments like Sales, R&D, and HR. It provides insights into employee turnover, job satisfaction, and education impacts to support HR in enhancing retention strategies.

## Objectives
1. **Identify Key Drivers of Attrition Across Departments**
   - Determine which factors contribute most significantly to employee turnover in various departments.
2. **Analyze Gender-Based Attrition Trends**
   - Explore if and how attrition rates differ between male and female employees and identify any significant patterns.
3. **Evaluate the Impact of Education Field on Employee Retention**
   - Assess how different educational backgrounds influence attrition rates and employee retention in the organization.
4. **Understand Demographic Trends in Employee Distribution**
   - Analyze how age and other demographic factors correlate with attrition rates across departments.
5. **Investigate Anomalies and Correlations in Attrition Data**
   - Identify any unusual patterns or correlations in the data that deviate from expected trends.

## North Star Metrics and Dimensions
### North Star Metrics
- **Attrition Rate:** Percentage of employees who left the organization compared to the total number of employees.
- **Employee Count:** Total number of employees within each department or role.
- **Job Satisfaction Ratings:** Ratings provided by employees reflecting their satisfaction levels.

### Dimensions
- **Department:** Sales, R&D, HR
- **Job Role:** Sales Executive, Sales Representative, Manager
- **Education Field:** Marketing, Technical Degree, Life Sciences, Medical
- **Age Group:** Age ranges segmented in bins (e.g., 20-24, 25-29, etc.)
- **Gender:** Male, Female

## Data Sourcing
The data for this analysis was meticulously sourced from a GitHub repository, which provided a clean, well-structured dataset. This repository facilitated an efficient extraction of valuable insights by offering a comprehensive and accessible data structure, ensuring the accuracy and relevance of our analysis.

## Summary of Insights
- **Departmental Attrition Comparison:** Sales has the highest attrition rate, followed closely by HR. However, R&D, despite having the largest workforce, shows high attrition in the 30-34 age group (20.27%), highlighting retention challenges in key demographics.
- **Role-Based Attrition in Sales:** Sales Representatives have the highest attrition (39.76%) across all satisfaction levels, especially in younger employees, while Sales Managers experience the lowest attrition.
- **Education Field Impact:** In Sales, the Marketing field shows the highest attrition rate (52.17%) in Sales Representative roles, particularly among younger employees (20-29). Similarly, high attrition is seen in Technical Degree holders.
- **Age-Based Attrition Trends:** Younger employees in Sales Representative and Technical Degree roles have high attrition, indicating possible misalignment with job expectations. Conversely, older Sales Executives face higher attrition than their younger counterparts, suggesting specific issues in this demographic.
- **R&D Role-Specific Issues:** High attrition in laboratory technician roles (42.11%) in R&D, predominantly among younger employees, requires attention.
- **Gender-Based Insights:** Slightly higher attrition is seen among male employees across departments, but the difference is not highly significant.

## Recommendations & Next Steps
- **Target Retention for Mid-Aged R&D Employees:** Investigate reasons behind the high attrition among employees aged 30-34 in R&D. Consider tailored retention programs, career progression pathways, or flexible working arrangements.
- **Address Sales Representative Attrition:** Focus on reducing the high attrition rates in Sales Representative roles, especially in Marketing and Technical Degree holders, by evaluating career alignment and support for younger employees.
  - **Investigate Education Field Misalignment:** Conduct deeper analysis into the Marketing and Technical Degree fields in Sales to explore misalignment between job roles and employee expectations, especially for younger employees.
- **Analyse Sales Executive Attrition:** Investigate the unusually high attrition rates among older Sales Executives (ages 45-54 and 50-55). Explore potential issues causing this trend, as older employees in this role face higher attrition rates compared to younger counterparts.
- **HR Attrition Monitoring:** While HR has a lower impact due to its small size, its high attrition rate should be monitored. Consider proactive engagement with young employees.
- **Gender-Specific Retention Strategies:** Continue to monitor gender-based trends in attrition and ensure no significant gaps emerge, particularly in departments with slightly higher male attrition rates.
