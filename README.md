# Employee Attrition Dataset Analysis

## Introduction

This repository contains an analysis of the "Employee Attrition" dataset, a synthetic dataset created by IBM for HR analytics simulations. The purpose of this analysis is to explore factors influencing employee attrition within a simulated environment, providing insights for organizations to enhance employee retention and job satisfaction.

## Dataset Description

- **Source**: The dataset is provided by IBM and is available on [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).
- **Motivation**: The study aims to understand the relationship between various employee-related factors and attrition rates to aid decision-making processes.
- **Variables**: The dataset includes a range of employee-related variables such as demographics, work-related data, compensation-related information, and employee satisfaction metrics.

## Univariate Statistics

- **Quantitative Variables**: Descriptive statistics and visualizations were conducted for quantitative variables including HourlyRate, DailyRate, DistanceFromHome, JobLevel, and PerformanceRating.
- **Categorical Variables**: Similar analyses were performed for categorical variables such as Department, JobRole, and EducationField.

## Outliers Identification

- Reviewed quantitative variables for potential outliers; no significant outliers were identified.
- Slight skewness was observed in some variables but deemed not significant enough to warrant exclusion.

## Cleaning Decisions

- Missing data: Rows with missing values in key variables were removed.
- Invalid data: Anomalies or data entries violating the data dictionary were corrected or investigated.

## Hypotheses Developed & Explained

1. **T-Test for Gender-Based Age Distribution**: Investigated age differences between male and female employees.
2. **Chi-squared Test for Gender and Attrition**: Explored the correlation between gender and attrition.
3. **ANOVA for Job Level and Performance Rating**: Analyzed performance ratings across different job levels.
4. **Odds Ratio (OR) Test for Overtime and Attrition**: Examined the odds of attrition between employees with and without overtime.
5. **Relative Risk (RR) Test for Job Role, Job Satisfaction, and Monthly Income**: Investigated the relative risk of unfavorable employee outcomes across different job roles, job satisfaction levels, and monthly income brackets.

## Analysis of FINER Questions

- **Finer Question 1**: Explored gender-based age distribution and disparities.
- **Finer Question 2**: Investigated gender-based salary distribution and department-specific headcounts.
- **Finer Question 3**: Examined the connection between job level and performance rating.
- **Finer Question 4**: Analyzed the difference in monthly income between employees with and without overtime.

## Conclusion

This analysis provides valuable insights into the factors influencing employee attrition within the simulated dataset. The findings can inform HR policies and practices aimed at enhancing employee retention and job satisfaction.

---

Feel free to customize and expand upon this README as needed for your project.
