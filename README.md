# Data Cleaning Project using MySQL

## Project Overview

This project focuses on cleaning and preparing a raw layoffs dataset using MySQL. 
The goal was to transform unclean data into a structured dataset ready for analysis.

## Tools Used

- MySQL
- SQL

## Data Cleaning Steps Performed

### 1. Removing Duplicates
- Created a staging table to preserve raw data
- Identified duplicate records using ROW_NUMBER() window function
- Removed duplicate entries

### 2. Data Standardization
- Removed extra spaces using TRIM()
- Standardized inconsistent industry values
- Converted date format into proper DATE format

### 3. Handling Missing Values
- Identified NULL and blank values
- Filled missing industry values using available company records

### 4. Removing Unnecessary Columns
- Removed helper columns after cleaning process

## SQL Concepts Used

- SELECT
- CREATE TABLE
- INSERT
- UPDATE
- DELETE
- JOIN
- CTE
- Window Functions
- ALTER TABLE

## Project Outcome

Successfully cleaned and transformed raw dataset into an analysis-ready format for further reporting and visualization.

## Screenshots

### Raw Dataset
![Raw Data](screenshots/raw_data.png)

### Duplicate Detection
![Duplicate Check](screenshots/duplicate_check.png)

### Data Standardization
![Industry Standardization](screenshots/industry_standardization.png)

### Final Clean Dataset
![Final Data](screenshots/final_cleaned_data.png)
