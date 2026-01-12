# Glassdoor-Gender-Pay-Gap-Analysis

Overview

This project analyzes Glassdoor salary data to identify gender pay disparities in the workplace. Using statistical and visual methods, it quantifies differences in pay while controlling for factors such as education, department, and seniority.

Objective

Investigate whether a gender pay gap exists.

Understand how factors like department, education, and seniority impact salary.

Provide actionable insights through data analysis and visualizations.

Key Features

Data Cleaning & Preparation: Removed missing values and created a total compensation (Salary) column.

Exploratory Data Analysis (EDA): Average salaries by gender, department, and education.

Visualizations:

Bar charts comparing salaries by department and education.

Scatterplot showing salary vs. seniority.

Boxplot displaying salary distribution by gender.

Hypothesis Testing:

Two-sided t-test for differences between male and female salaries.

One-sided t-test to check if males earn more than females.

Multiple Linear Regression: Controlled for education, department, and seniority to quantify adjusted gender pay gaps.

Insights

Males earn about $8,749 more on average than females in comparable roles after controlling for other factors.

Seniority and education positively impact salary.

Certain departments (Sales, Engineering, Management) show higher average salaries for males.

Regression explains ~35% of salary variation, indicating additional factors also contribute to pay differences.

Technologies & Tools

Languages & Libraries: R, tidyverse, dplyr, ggplot2

File Formats: CSV for input dataset, RMarkdown for reproducible analysis

Usage

Clone the repository.

Place glassdoor_data.csv in the project folder.

Open gender_pay_gap.Rmd in RStudio and knit to HTML or PDF.

Explore the plots, tables, and regression summary in the generated report.
