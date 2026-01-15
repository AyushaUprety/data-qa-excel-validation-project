Data QA and Validation Project (Excel)

Overview
This project focuses on manual Data Quality Assurance performed on a messy dataset using Microsoft Excel (Web). The purpose of the project is to inspect, validate, and document data quality issues commonly found in real-world datasets, especially those generated from web scraping or large data pipelines. The dataset was not cleaned or modified; the work strictly demonstrates detection and reporting of issues.

Dataset Description
The dataset contains the following columns:
Name, Gender, Age, City, Department, Salary, Email

The data includes duplicates, missing values, formatting inconsistencies, and minor errors to simulate realistic QA scenarios.

QA Checks Performed

Missing Value Checks
Each column was checked for missing values using helper columns and logical formulas. No missing values were found in Name, Gender, Salary, or Email. Missing values were detected in the Age column.

Duplicate Analysis
Duplicate values were identified in both the Name and Email columns using helper columns. All names appear multiple times in the dataset. Duplicate emails were also observed. These duplicates were not removed because other fields such as Age, City, Gender, Department, and Salary differ across rows, representing realistic data variation rather than exact duplicates.

Formatting and Consistency Checks
Text consistency checks were performed on City and Department columns to identify capitalization inconsistencies. Extra whitespace issues were detected in a small number of Department values using trimming checks. Email values were reviewed for formatting consistency, and some email domain typos were identified, such as variations in common domains.

Salary Validation
The Salary column was validated to ensure all values were numeric and present. No missing or invalid salary values were found.

Full Row Duplicate Check
A row-level duplicate check was performed across all columns to identify exact duplicate records. No completely identical rows were found, confirming that the dataset contains partial duplicates but no exact row duplicates.

Visual Highlighting
Helper columns were used to display TRUE/FALSE results for each QA check. Conditional formatting was applied to highlight detected issues, making it easier to visually identify problematic records during review.

Tools Used
Microsoft Excel (Web)
Excel helper columns
Conditional formatting
Excel Formulas

Key Learnings
This project helped develop a strong understanding of manual data QA processes, including how to systematically validate data quality, detect inconsistencies, and document findings without altering the original dataset. It reflects the type of data validation work required when reviewing scraped or large datasets.

Conclusion
This project demonstrates a structured and practical approach to manual Data Quality Assurance, focusing on accuracy, consistency, and clear documentation rather than data cleaning or transformation.

