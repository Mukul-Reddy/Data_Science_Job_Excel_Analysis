# Data_Science_Job_Excel_Analysis
Analysis of data science jobs using MS Excel  
Data - [Luke Barousse](https://github.com/lukebarousse/Excel_Data_Analytics_Course/blob/main/0_Resources/Datasets/data_jobs_salary_all.xlsx)

## Project 1 - Dashboard 
In this project, I created an interactive dashboard in Excel. 

![Screenshot 2025-02-18 151647](https://github.com/user-attachments/assets/cbf018f0-f084-4fca-a62d-000115363109)

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
In this Project, I analysed the data in Excel with the help of Power Query and Power Pivot.  

### Skills:
- Pivot Tables
- Pivot Charts
- Power Query
- Power Pivot
- DAX

### Questions Analysed:  

**1. Who earns more: professionals paid an hourly rate or those on a yearly salary?**  

![image](https://github.com/user-attachments/assets/c7ac5d25-8ac1-4fd8-ba56-1291af9ebe0d)

As you can see, those who are paid on yearly basis earn more than those who are paid by the hour.  
*I took 2080 hours as working hours in a year*  


**2. What are the top 10 skills for each job?**  

![image](https://github.com/user-attachments/assets/cdc6c69e-8eba-4412-80e8-c685d30349be)  

For all the jobs, the top 10 skills are:  

1. SQL
2. Python
3. Tableau
4. R
5. AWS
6. Excel
7. Spark
8. SAS
9. Azure
10. Java


**3. Does more skills mean more salary?**

![image](https://github.com/user-attachments/assets/b54079a9-5af1-4cb8-af3a-80f78a2b82a9)

As you can see, there is a positive correlation between number of skills per job and median salary.  


**4. What is the pay of top 10 skills?**

![image](https://github.com/user-attachments/assets/eb43259d-64ac-4979-8f8a-86760711b120)

Skills like Pyhton, Java, AWS, Spark have higher median salaries.  
Learning these skills can give better job opportunities.








