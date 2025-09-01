#  Jobs Postings 2024 - Dashboard

## 📌Table of Contents
- [Overview](#overview)
- [Objective](#objective)
- [Project Structure](#project-structure)
- [Datasets](#datasets)
- [Business Problem](#business-problem)
- [Tools & Technologies](#tools--technologies)
- [Dashboard](#dashboard)
    - [Main Sheet](#main-sheet)
    - [Job Drill Sheet](#job-drill-sheet)
- [How to Run This Project](#how-to-run-this-project)
- [Author & Contact](#author--contact)

---

## Overview
<p align="justify">

This Power BI dashboard is built to analyze and visualize job postings for 2024. The dashboard provides insights into employment trends, job positions, industries, locations, and work preferences to help users understand the job market better.

</p>

---

## Objective
<p align="justify">

1. **Import Data** - Use Power Query to import the raw data from your SQL database or local host into the Data pane.

2. **Data Cleaning** - Utilize Power Query Editor to refine, clean, and structure the dataset, ensuring it is ready for analysis and meaningful insights.

3. **Data Visualization** - Use the Visualization pane to build a compelling visual story. It enables the business to track the sales performance, identify growth opportunities, and make data-driven decisions..

</p>
--- 

## Project Structure
```
Job-Postings-2024-PowerBI-Dashboard-Project4/
│
├── 1) Datasets /                       #CSV Data File
│      ├── company_dim.csv
│      ├── job_postings_fact.csv
│      ├── skills_dim.csv
│      └── skills_job_dim.csv
│
├── Images /                            #Folder
│       ├── Icon /                      #Folder
│       ├── Dashboard - Main.PNG   
│       └── Dashboard - Job Drilling.PNG
│
├── Job Posting 2024 - Dashboard.pbix   #PowerBi file        
├── README.md


```

---

## Datasets

<p align="justify">

1. company_dim.csv - A dimension table that stores company-related data.
2. skills_dim.csv - A dimension table that provides skills details.
3. skills_job_dim.csv - A fact table that acts as a bridge to create a connection between skills_dim.csv & job_postings_fact.csv
4. job_postings_fact.csv - Serves as the fact table, containing job vacancy data along with foreign keys linking to all dimension tables.

</p>

---

## Business Problem

- Interactive dashboard with filters and slicers.
- Analysis of job postings by industry, company, and job role.
- Location-based insights (city, state, and region level).
- Employment type breakdown (remote, hybrid, onsite).
- Salary trends and demand analysis.
- Skills and requirement trends

---

## Tools & Technologies

1. Microsoft Power BI Features:
- Power Query – Data Loading
- Power Query Editor – Data Cleaning & Transformation

2. Power BI Core Functions:
- Report View – Dashboard Building
- Model View – Relationship Creation
- Measures & Columns (DAX) – Calculations & Formulas
- Slicers – Data Filtering

3. Version Control & Collaboration:
- GitHub – Project Hosting & Sharing

---


## Dashboard

### Main Sheet
![Dashboard Preview](Image/Dashboard_Main.PNG)

#### Features :
- Work Role – Total number of job postings categorized by role.
- Skill Requirement – Highlights the most in-demand skills for job postings.
- Schedule – Around 80% of the jobs are full-time positions.
- Remote – Only 1 out of 8 jobs a remote opportunities.


### Job Drill Sheet
![Dashboard Preview](Image/Dashboard_Job_Drilling.PNG)

#### Features :
- Yearly Salary – Displays the median, maximum, and minimum annual salaries.
- Hourly Salary – Shows the median, maximum, and minimum hourly wages.
- Skill Requirement – Highlights the top in-demand skills for different job roles.
- Country – Presents job role demand across the top 10 countries.

---

## How to Run This Project
1. Download the .pbix file from this repository.
2. Open it in Power BI Desktop.
3. Explore the dashboard and interact with filters, slicers, and charts.
4. Use Slicer to filter data by
    - Country
    - Work Role
    - Month
    - Schedule
5. Download the data file from this repository.
6. Change the Data Source Location, to load the data in Power Query .
7. Utlize the Power Query to transform the data.
8. Use Dax Formula, to create custom calculation on the data.
9. Use Drill Through to explore job role–specific information.

---
    
## Author & Contact

**Sagar Kumar Mandle** <br>

  
📧 Email: sagarmandle11135@gmail.com 

🔗 [LinkedIn](https://www.linkedin.com/in/sagar-kumar-mandle-7086ba366/)


