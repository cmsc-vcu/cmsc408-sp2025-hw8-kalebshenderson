Homework 8 - World Bank Indicator Analysis

## Overview

In this assignment, I analyzed World Bank country and indicator data by loading CSV files into a MySQL database.  
I performed various SQL queries to explore relationships between countries, regions, and income groups, and created tables and percentages to visualize global patterns.

The project included:
- Loading and cleaning data into a MySQL database.
- Using advanced SQL features like aggregation, CASE statements, Common Table Expressions, joins, and subqueries.

---

## Files and Structure

 `report.qmd`    Main Quarto file with all code, analysis, and outputs 
 `report.html`   Final rendered HTML report 
 `.env`          Environment variables for database connection 
 `helpers.py`    Python helpers to connect to the database 
 CSV Files       Original World Bank CSVs (e.g., `WDICountry.csv`, `WDI_Series_Time.csv`) 

---

## Requirements

Before running the project, you need:

- **Python**
- **MySQL database** 
- Python libraries:
  - `pymysql`
  - `sqlalchemy`
  - `pandas`
  - `dotenv`
- **Quarto** 

## Final Thoughts

This assignment helped reinforce key SQL concepts while practicing real-world data cleaning, organization, and reporting.  
It also introduced the challenges of working with external datasets where not everything is clean or consistent. The most dificult challenge for me however, was getting python to read my .env file, as that is where unfortunately I spent most of my time on this assignment.

Using MYSQL for hosting and Quarto for documentation made the workflow much closer to real-world data science and analytics practices.
