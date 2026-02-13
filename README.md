# Job Market Analysis using Machine Learning

## Project Overview

This project analyzes 1.3+ million LinkedIn job postings to identify skill demand trends, role-based skill requirements, and job market patterns. 

The objective is to understand:
- Which skills are most demanded?
- What skills are required for specific job roles?
- Which countries provide the highest job opportunities?
- How skill distribution varies across job roles?

## Dataset

- Source: Kaggle – LinkedIn Jobs & Skills (2024)
- Total Records: 1.3 Million job postings
- Key Columns Used:
  - job_title
  - job_skills
  - job_location
  - first_seen
  - search_country

## Data Engineering & Preprocessing

-> Removed missing values  
-> Merged job_skills and job_postings datasets  
-> Validated merge loss (< 0.002%)  
-> Converted date columns to datetime  
-> Exploded multi-skill cells into individual skill rows  
-> Removed statistical outliers using IQR method  
-> Handled large dataset efficiently  

## Exploratory Data Analysis

### 1. Role-Based Skill Profiling
Identified top skills required for a specific job role using a user-defined function.

### 2️. Top 10 Most Demanded Skills
Analyzed overall market demand distribution.

### 3️. Country-wise Job Distribution
Visualized which countries offer the highest number of job opportunities.

### 4️. Skill Distribution Analysis
Used:
- Box Plot: to understand distribution and outliers in skill requirements.

## Key Insights

- Python and SQL dominate data-related roles.
- Skill demand distribution is right-skewed.
- A small number of jobs list unusually high skill requirements (outliers).
- Role-specific skill bundles are clearly visible.

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Git & GitHub

## Author

Krittika S 
Aspiring Data Engineer / Data Scientist / Data Analyst
