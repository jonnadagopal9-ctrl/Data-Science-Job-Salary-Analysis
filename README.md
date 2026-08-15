# Data Science Job Salary Analysis

## 📊 Project Overview

This project performs an exploratory data analysis (EDA) of job salary data to identify salary patterns and trends based on experience level, work type, job title, and location.

The project uses Python and data analysis libraries to clean, transform, analyze, and visualize job salary information.

## 🎯 Objectives

- Analyze salary distributions across job postings
- Compare salaries across different work types
- Study salary trends by experience level
- Identify common and high-paying job titles
- Analyze salary differences across locations
- Examine relationships between minimum and maximum salaries
- Analyze available remote-work information
- Create a visual salary analysis dashboard

## 🗂️ Dataset

The dataset contains job posting information including:

- Job ID
- Company name
- Job title
- Location
- Minimum salary
- Maximum salary
- Pay period
- Currency
- Work type
- Experience level
- Job views
- Remote-work information

The original dataset contains **123,849 job postings and 31 columns**.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Google Colab
- GitHub

## 🔍 Data Analysis

The project includes analysis of:

### Salary Distribution
Analyzed the distribution of annual maximum salaries and identified the effect of extreme salary values.

### Work Type
Compared median salaries across:

- Contract
- Full-time
- Other
- Temporary
- Internship
- Part-time
- Volunteer

### Experience Level
Analyzed salary differences across experience levels and found that senior and executive positions generally have higher salary ranges.

### Job Titles
Identified the most common job titles and analyzed job titles with high total job views.

### Location
Compared salary levels across different job locations and identified locations with higher median salaries.

### Remote Work
Analyzed available remote-work information. Because most records have missing remote-work values, the remote salary comparison is treated as a descriptive finding rather than a reliable remote vs. non-remote comparison.

### Salary Correlation

Key correlations identified:

- Minimum salary vs. maximum salary: **0.67**
- Annual minimum salary vs. annual maximum salary: **0.84**

These results indicate a positive relationship between minimum and maximum salary values.

## 📈 Interactive Dashboard

The project includes a salary analysis dashboard containing:

- Top 10 job titles by number of postings
- Median salary by work type
- Median salary by experience level
- Top job locations

## 💡 Key Findings

- Salary generally increases with experience and seniority.
- Executive and senior-level positions tend to have higher salaries.
- Contract and full-time positions show relatively high median salaries.
- Technology and major business hubs tend to offer higher-paying opportunities.
- Specialized professional and senior management roles appear among higher-paying positions.
- Higher minimum salaries are generally associated with higher maximum salaries.

## 📁 Project Structure

```text
Data-Science-Job-Salary-Analysis/
│
├── Data_Science_Job_Salary_Analysis.ipynb
└── README.md
