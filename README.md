# ABC-Company-data-analysis
Exploratory data analysis on ABC Company employee dataset using python


# Project Overview
This project analyzes employee data from ABC Company to gain insights into workforce distribution, salary expenditure, age patterns, and correlations. The dataset contains 458 rows and 9 columns, including information such as Name, Team, Position, Age, Height, Weight, College, and Salary. The goal of this project is to preprocess, analyze, and visualize the data using Python, Pandas, Seaborn, and Matplotlib.

# Preprocessing Steps
- Height Column Correction: Replaced values in the "Height" column with random numbers between 150 and 180 to ensure data consistency.  
- Identified missing value in College.   
-  Ensured numeric columns.

# Analysis Tasks

Employee Distribution Across Teams: 
- Counted the number of employees per team.  
- Most teams have 14–15 members.  
- "New Orleans Pelicans"  has the highest count with 19 members.  
- Every team has at least 14 employees.  


Percentage Distribution of Employees by Team:
- Calculated percentage of employees in each team relative to total workforce.  
- New Orleans Pelicans has the highest percentage of employees.   


Employee Distribution by Position
- Counted the number of employees in each position.  
- SG:  102 employees (most common).  
- C: Fewest employees, representing 17.2% of workforce.  


Predominant Age Group
- Created a new column "Age_Group" to categorize employees.  
- Predominant age group:20–29 years, indicating a young workforce.  
- Visualization:Count plot.

Salary Expenditure by Team and Position
- Calculated total salary expenditure per team and per position.  
- Highest Salary: 
  - Team: Cleveland Cavaliers
  - Position: C  
- Lowest Salary:
  - Team: Philadelphia 76ers  
  - Position: Shooting Guard (SG)  


 Correlation Between Age and Salary
- Calculated correlation coefficient: 0.21, indicating a slight positive correlation.  
-  Older employees tend to earn slightly more, but salary is influenced more by position and role.  
- Visualization: correlation heatmap for numeric features.



# Key Insights & Trends
- Workforce is evenly distributed across teams, with minor variations.  
- SG and PF are the most common positions.  
- Most employees are in the 25–29 age group, showing a predominantly young workforce.  
- Salary expenditure is aligned with role importance and team performance, not merely employee count.  
- Slight positive correlation exists between Age and Salary, suggesting experience moderately affects pay.  



# Tools and Libraries Used
- Programming Language:Python  
- Data Analysis: Pandas, NumPy  
- Data Visualization: Seaborn, Matplotlib  



