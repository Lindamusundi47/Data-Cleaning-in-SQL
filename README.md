# Data-Cleaning-in-SQL

### Project Overview
This project focuses on cleaning and preparing a layoffs dataset using SQL.I created staging tables, identified and removed duplicates, standardized inconsistent fields, and resolved missing values through .

### Data Source

Layoff Data:The primary dataset used for this analysis is the "layoffs.csv" file, detailed information about layoffs from different companies.

### Tools

-MySQL -Data Cleaning 

### Data Cleaning/Preparation

In the initial data preparation phase ,I performed the following task;

  1.Created a staging table to preserve the raw data.
  
  2.Identified duplicate records using ROW_NUMBER().
  
  3.Standardized company, industry, country, and date fields.
  
  4.Replaced blank values with NULL where appropriate.
  
  5.Filled missing industry values using self-joins.
  
  6.Removed records with no meaningful layoff information.
  
  7. Dropped temporary columns used during cleaning.
     

### 
