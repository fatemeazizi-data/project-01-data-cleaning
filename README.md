# project-01-data-cleaning
Data Cleaning Project
Overview
This project focuses on cleaning, standardizing, and preparing raw customer data for analysis and reporting.
The data cleaning process was performed using Microsoft Excel and Power Query.
Objectives
•	Identify data quality issues
•	Clean and standardize raw data
•	Handle missing and invalid values
•	Check duplicate Customer IDs
•	Validate Province and City data
•	Prepare the final dataset for analysis and reporting
Data Quality Issues
The raw dataset contained:
•	Null values
•	Zero values
•	Duplicate Customer IDs
•	Extra spaces and non-printable characters
•	Inconsistent Gender values
•	Inconsistent Province and City names
•	Data type issues
Cleaning Process
Raw Data
   ↓
Data Type Check
   ↓
Text Cleaning
   ↓
Standardization
   ↓
Null / Zero Handling
   ↓
Quality Checks
   ↓
Final Data
Quality Checks
•	Duplicate Check
•	Null Check
•	Zero Check
•	Invalid Value Check
•	Gender Check
•	Province Check
•	City Check
Key Approach
The raw data was preserved and the cleaning process was performed in Power Query.
Reference queries were used for quality checks, making the process repeatable after each refresh.
Tools
•	Microsoft Excel
•	Power Query
Project Structure
project-01-data-cleaning/
│
├── README.md
├── data/
│   └── cleaned_dataset.xlsx
│
├── notebook/
│   └── data_cleaning.ipynb
│
└── report/
    └── analysis_report.pdf
Result
The final dataset is cleaned, standardized, and ready for data analysis, reporting, and dashboard development.

