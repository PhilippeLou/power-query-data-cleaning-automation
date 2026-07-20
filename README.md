# Excel Power Query — Data Cleaning & Automation

This repo documents a set of hands-on Excel exercises focused on **data cleaning, combining files, and automation using Power Query**, followed by basic analysis (pivot table + chart) built on top of the cleaned data.

## 📁 Project Overview

The goal of these exercises was to practice real-world data analyst workflows:
- Combining messy, multi-sheet/multi-file data into a single clean table
- Cleaning and standardizing raw data (types, formatting, duplicates)
- Automating the combine process using Power Query custom functions
- Summarizing and visualizing the cleaned data with a pivot table and chart

---

## Lesson 1: Combine Multiple Excel Files & Sheets Automatically

Combined multiple sheets into a single unified **Sales Data** table using Power Query.

**Key steps:**
- Loaded source data and removed unneeded columns
- Added and expanded a custom column to pull in data from all sheets
- Promoted headers and set correct data types
- Renamed columns for consistency
- Filtered rows and extracted first characters for categorization
- Split a column by delimiter and re-applied data types
- Added a custom column, removed unneeded columns
- Reordered final columns for readability

---

## Lesson 2: Data Cleaning in Excel (Power Query)

Cleaned and standardized the combined sales data.

**Key steps:**
- Removed duplicate records
- Set correct data types
- Inserted a date subtraction column for date-based calculations
- Reordered and renamed columns for clarity
- Trimmed text and capitalized each word for consistent formatting
- Replaced values and merged columns as needed
- Split a column by delimiter and re-typed resulting columns
- Added custom columns and removed unneeded ones
- Final column reorder and rename for readability

**Additional analysis on the cleaned data:**
- Payment method analysis across transactions
- Days of delivery analysis using date subtraction

---

## Lesson 3: Excel Automation — Combine Multiple Files Using Power Query

Automated the file-combining process using a Power Query custom function, making it scalable and repeatable.

**Key steps:**
- Filtered hidden files from the source folder before processing
- Invoked a custom function to process each file automatically
- Renamed and removed unneeded columns
- Expanded a table column to bring in combined file data
- Set correct data types and filtered rows
- Inserted a multiplication column for calculated values
- Final column rename and reorder for readability

---

## Analysis: Pivot Table & Chart

Built on top of the cleaned/combined dataset from the Power Query steps above.

**Pivot Table:**
- Rows: Month
- Columns: Ship Mode
- Values: Sum of Sales Amount

**Chart:**
- Visualizes Sum of Sales Amount by Month, broken down by Ship Mode
- Source: the pivot table above

---

## Skills Demonstrated
- Power Query (M-based ETL): combining, cleaning, transforming data
- Custom functions for repeatable/scalable automation
- Data type management, text standardization, duplicate handling
- Pivot tables and charting for summarized insights
