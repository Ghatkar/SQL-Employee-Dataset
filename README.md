## SQL-Employee-Dataset

## Overview
This is a group project that demonstrates SQL database design and data analysis using an Employee Management System. 
It includes creating a relational database, populating it with sample data, and performing analytical queries to generate business insights.

## Objectives
- Design a relational database using SQL.
- Establish relationships using primary and foreign keys.
- Populate tables with sample organizational data.
- Perform analytical queries to answer business questions.
- Generate reports and derive insights 

## Database Schema

The database consists of four related tables:

- Departments – Department details and locations.
- Employees – Employee information and department assignments.
- Projects – Projects handled by different departments.
- Timesheets** – Employee working hours on various projects.

## Entity Relationships
- One Department → Many Employees
- One Department → Many Projects
- One Employee → Many Timesheet Entries
- One Project → Many Timesheet Entries

## Skills gained 
- MySQL
- Relational Database Design
- Data Modeling
- SQL Query Writing
- Data Aggregation
- Business Analysis
- Window Functions
- Subqueries
- Canva
  
## Queries solved 

### 1. Employee Productivity Ranking
Calculated the total hours worked by each employee and ranked them using the **RANK()** window function.

### 2. Above Average Employees
Identified employees whose total working hours exceeded the overall average using a nested subquery.

##Files 
+ SQL file
+ Presentation of project

