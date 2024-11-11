# AtliQ Technologies Sales and Financial Reports (2019-2021)

This project provides a comprehensive analysis of AtliQ Technologies' sales and financial performance over three years (2019, 2020, 2021).

### Step 1: Data Extraction
- Extracted data from external CSV files containing sales and financial information from 2019 to 2021.

### Step 2: Data Cleaning and Transformation
- Used **Power Query** to:
  - Clean data by removing null values, duplicates, and ensuring consistency.
  - Created a **Date Table** to help in organizing reports by calendar and fiscal years.
  - Converted calendar year data into fiscal years and further into quarters.

### Step 3: Data Loading and Modeling
- Loaded transformed tables into the Data Model, then joined tables by defining relationships based on key columns.
- This allowed for efficient data organization and accurate cross-table analysis.

### Step 4: Data Analysis and Calculation with DAX
- Created calculated columns and measures using **DAX formulas** to support analysis. Examples:
  - Custom P&L metrics
  - Gain Margin (GM%) by quarters
- Used Pivot Tables to display data visually, summarizing complex data.

### Step 5: Report Preparation
- Developed the following reports:
  1. **Sales Report - Customer Performance**
  2. **Sales Report - Market Performance vs Targets**
  3. **Financial Report - P&L Statements Yearwise, Monthly, Marketwise**
  4. **Financial Report - GM% by Quarters**


###Technical Skills Gained
ETL Proficiency: Demonstrated capability in Extract, Transform, Load (ETL) processes using Power Query for efficient data handling and transformation.
Date Table Creation: Mastery in generating custom date tables to support fiscal and calendar-based reporting.
Fiscal Analysis: Expertise in deriving fiscal quarters and months, enabling time-based analysis for more granular financial insights.
Data Modeling with Power Pivot: Experience in creating relationships across datasets to unify reports within a cohesive data model.
Advanced DAX Usage: Skilled in Data Analysis Expressions (DAX) to create complex measures and calculated columns, enabling sophisticated data analysis.
