# Data_Science_Job_Excel_Analysis
Analysis of data science jobs using MS Excel  
Data - [Luke Barousse](https://github.com/lukebarousse/Excel_Data_Analytics_Course/blob/main/0_Resources/Datasets/data_jobs_salary_all.xlsx)

## Project 1 - Dashboard 
In this project, I created an interactive dashboard in Excel. 

![Screenshot 2025-02-18 151647](https://github.com/lukebarousse/Excel_Data_Analytics_Course/blob/main/0_Resources/Datasets/data_jobs_salary_all.xlsx)

Median Formula Used: 

```
=MEDIAN(
IF(
    (jobs[job_title_short]=A2)*
    (jobs[job_country]=country)*
    (ISNUMBER(SEARCH(type,jobs[job_schedule_type])))*
    (jobs[salary_year_avg]<>0),
    jobs[salary_year_avg]
)
)
```

### Skills Used: 
- Formulas and Functions
- Charts
- Data Validation

## Project 2 - Data Analysis

