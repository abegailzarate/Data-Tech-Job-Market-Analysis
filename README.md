# Data & Tech Job Market Analysis

## Project Dashboard

<img width="800" height="312" alt="ezgif com-video-to-gif-converter" src="https://github.com/user-attachments/assets/edf0efae-b441-4a0a-a612-ce52621d0ca7" />


## Project Overview

This project analyzes trends in the Data and Technology job market to identify patterns in job demand, salaries, employment types, work arrangements, hiring companies.

An interactive dashboard was developed using Microsoft Excel to visualize key findings and makes the analysis easier to explore and understand.    

 **[View the Interactive Dashboard](https://1drv.ms/x/c/bdbd7a126eba8b06/IQCqGpsJQZ3sSImPRQ-TiJwvAY6kdhZ4qgynLBAqo0bC8xs?e=ysqmdd)**

## Objectives
* Identify the job positions with the highest demand.
* Determine the most common employment types.
* Analyze the distribution of remote and on-site work arrangements.
* Analyze salary trends across different job positions based on selected filters.
* Identify the companies with the highest number of job postings.
* Examine degree requirements across job postings.
  
## Analysis Process

1. **Data Analysis:**
   Applied Excel formulas and functions to analyze and filter the dataset, including:
   - IF
   - COUNTIFS
   - MEDIAN
   - ISNUMBER
   - NOT
   - SEARCH
   - UNIQUE
   - SUM
   - Sorting & Filtering
  
2. **Data Visualization:**
   - KPI cards & charts to present key findings.
   - Developed an Interactive Dashboard.
   - Implemented data validation dropdowns for dynamic filtering.

## Dashboard Components
The dashboard includes the following:

### Data Validations
* Job positions
* Country
* Employment type
* Work arrangement

### KPI Cards
* Total job Positions
* Total companies
* Median salary
* Work arrangement Percentage

### Visualizations
* Jobs by position
* Median salary by position
* Top hiring companies
* Employment types
* Remote vs. on-site work arrangement
* Degree requirements

# Dashboard Preview

### Data Validations
<img width="187" height="332" alt="Screenshot 2026-09-04 174525" src="https://github.com/user-attachments/assets/fb07d804-6d97-4d56-870c-c4c7b05f752a" />

* Used UNIQUE to generate unique filter values.
* Implemented data validation dropdowns for Job Position, Country, Employment Type, and Work Arrangement.
* Enabled dynamic filtering of the dashboard.
  
### KPI Cards
<img width="912" height="112" alt="Screenshot 2026-09-04 180438" src="https://github.com/user-attachments/assets/1b58e336-6bf3-4f04-a2f7-18d967d2add7" />

* Used KPI Cards for total jobs, total companies, median salary, work arrangements percentage.
* Used COUNTIFS to calculate the number of job postings based on selected filters.
* Used a filtered MEDIAN calculation to determine salary statistics based on selected filters.

### Charts
<img width="1065" height="431" alt="Screenshot 2026-09-04 201228" src="https://github.com/user-attachments/assets/6d614776-ce2b-49b6-bd2a-3cdb83352655" />

* **Job Demand by Job Position.**
  - Used COUNTIFS to calculate the number of job posting per job position
  - Applied IF logic to dynamically highlight the selected job position.
  - Visualized job demand using column chart

 * **Employment Type**
   - Used UNIQUE to identify employment types.
   - Used SORT and FILTER to organize and retrieve relevant values.
   - Used SEARCH, ISNUMBER, NOT to identify employment type within job postings.
   - Used Bar Chart.

* **Job Position by Salary**
   - Used MEDIANIF formula to determine the median salary for each job position.
   - Salary results dynamically respond to the selected dashboard filters.
   - Visualize salary trends using Column Chart.
     
* **Top Companies**
  - Used UNIQUE to identify the hiring companies.
  - Used COUNTIFS to calculate the number of job posting per company.
  - Sorted results to rank companies by number of job postings.
  - Visualized results using a bar chart.

* Remote vs On-site Work Arrangement
  - Used IF logic to convert logical values into Remote and On-site categories.
  - Used COUNTIFS to calculate the number of postings for each arrangement.
  - Calculated percentages using SUM and division.
  - Visualized the distribution using a pie chart.
 
* **Has Degree VS No Degree**
  - Used COUNTIFS to get the count of Has Degree and no degree.
  - Used COUNTIFS to calculate job postings requiring a degree versus those without a degree requirement.
  - Visualized results using bar chart.

  ## Tools Used

**Microsoft Excel**

* Formulas & Functions
* Data validation
* Charts & Visualizations
* Statistical analysis
* Dashboard development
* Data filtering & sorting






