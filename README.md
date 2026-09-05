# Data & Tech Job Market Analysis

## Project Dashboard

<img width="800" height="312" alt="ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/edf0efae-b441-4a0a-a612-ce52621d0ca7" />


## Project Overview

This project analyzes trends in the Data and Technology job market to identify patterns in job demand, salaries, employment types, work arrangements, hiring companies.

An interactive dashboard was developed using Microsoft Excel, allowing users to explore the data through dynamic filters and visualizations. 

 **[View the Interactive Dashboard](https://1drv.ms/x/c/bdbd7a126eba8b06/IQCqGpsJQZ3sSImPRQ-TiJwvAY6kdhZ4qgynLBAqo0bC8xs?e=ysqmdd)**

## Objectives
* Identify the job positions with the highest demand.
* Determine the most common employment types.
* Examine remote and on-site work arrangements.
* Analyze salary trends across different job positions based on selected filters.
* Determine the companies with the highest number of job postings.
* Analyze degree requirements across job postings.
  
## Analysis Process

### Tools Used

**Microsoft Excel**

* Formulas & Functions
* Data validation
* Charts & Visualizations
* Statistical analysis
* Dashboard development
* Data filtering & sorting

Applied Excel formulas and functions to analyze and filter the dataset, including:
   - IF
   - COUNTIFS
   - MEDIAN
   - ISNUMBER
   - NOT
   - SEARCH
   - UNIQUE
   - Sorting & Filtering

## Visualizations
### Interactive Filters
* Job positions
* Country
* Employment type
* Work arrangement

### KPI Cards

The dashboard displays four key metrics:

* Total job Positions
* Total companies
* Median salary
* Work arrangement Percentage

**COUNTIFS** was used to calculate job posting, total companies, and work arrangement percentage counts based on the selected filters, while a filtered **MEDIAN**calculation was used for salary analysis.

# Dashboard Preview

### Data Validations
<img width="187" height="332" alt="Screenshot 2026-09-04 174525" src="https://github.com/user-attachments/assets/fb07d804-6d97-4d56-870c-c4c7b05f752a" />

* Used UNIQUE to generate unique filter values.
* Implemented data validation dropdowns for the dashboard filters.
* Connected the selected filter values to the dashboard calculations.
* Enabled dynamic filtering of the dashboard.
  
### KPI Cards
<img width="912" height="112" alt="Screenshot 2026-09-04 180438" src="https://github.com/user-attachments/assets/1b58e336-6bf3-4f04-a2f7-18d967d2add7" />

* Used COUNTIFS to calculate the number of job postings based on selected filters.
* Used a filtered MEDIAN calculation to determine salary statistics based on selected filters.
* Calculated remote work percentage based on filtered job postings.
* Designed KPI cards to provide a quick overview of the selected data.

### Charts
<img width="1065" height="431" alt="Screenshot 2026-09-04 201228" src="https://github.com/user-attachments/assets/6d614776-ce2b-49b6-bd2a-3cdb83352655" />

* **Job Demand by Job Position.**
   * Used COUNTIFS to calculate the number of job posting per job position
   * Applied IF logic to dynamically highlight the selected job position.
   * Used a column chart to compare job demand across positions.

 * **Employment Type**
   * Used UNIQUE, SORT, and FILTER to generate and organize employment type categories.
   * Used SEARCH and ISNUMBER to identify employment types within job postings.
   * Visualized the distribution using a bar chart.

* **Job Position by Salary**
   * Used filtered MEDIAN calculations to determine the median salary for each position.
   * Salary results dynamically respond to the selected dashboard filters.
   * Used a column chart to compare salary levels across positions.
     
* **Top Companies**
  * Used UNIQUE to identify the hiring companies.
  * Used COUNTIFS to calculate the number of job posting per company.
  * Sorted results to rank companies by number of job postings.
  * Used bar chart to visualize the top hiring companies

* **Remote vs On-site Work Arrangement**
  * Used IF logic to categorize work arrangements as Remote or On-site.
  * Used COUNTIFS to calculate the number of postings for each arrangement.
  * Calculated percentages using filtered counts.
  * Visualized the distribution using a pie chart.
 
* **Has Degree VS No Degree**
  * Used COUNTIFS to calculate job postings with and without a stated degree requirement.
  * Compared the distribution of postings based on degree requirements.
  * Visualized the results using a bar chart.

## Key Insights

Based on the analyzed job postings and the selected dashboard filters, the following insights were identified:

* **Job Demand:**
  Data Analyst had the highest number of job postings among the analyzed positions, followed by Data Engineer and Data Scientist.
  
* **Work Arrangement:**
  Under the selected filters, **92% of job postings were on-site**, while **8% were remote**.
  
* **Salary:**
  Median salaries varied across job positions. Senior Data Analyst had the highest median salary at approximately **₱111,175**, followed by Data Engineer at **₱96,773**.
  
* **Employment Type:**
  Full-time positions were the most common employment type in the dataset.
  
* **Hiring Companies:**
  The dashboard shows that job postings were distributed across many companies, with some companies having a higher number of postings than others.
  
* **Degree Requirements:**
  Job postings varied in their degree requirements, with opportunities available both for roles requiring a degree and roles without a stated degree requirement.

These insights provide an overview of job demand, salary levels, work arrangements, employment types, hiring companies, and educational requirements within the Data and Technology job market.

## Project Outcome

The completed dashboard provides an interactive way to explore Data and Technology job postings based on job demand, salary, employment type, work arrangement, hiring company, and degree requirements.

This project demonstrates practical experience in:

* Microsoft Excel
* Data Analysis
* Statistical Analysis
* Data Visualization
* Dashboard Development
* Dynamic Filtering
* Business-oriented Insight 


