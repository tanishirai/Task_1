# Data Cleaning and Preparation Using Microsoft Excel

## Overview

This project involves cleaning and preparing a dataset using Microsoft Excel. The dataset was thoroughly checked and processed to ensure consistency, accuracy, and readiness for analysis.

## Steps Performed

### 1. Identify and Handle Missing Values
- Used **Conditional Formatting** to highlight blank cells.
- Applied filtering to display blanks only and deleted rows with missing values.
- No missing values were found in this dataset.

### 2. Remove Duplicate Rows
- Used Excel's **Remove Duplicates** feature on all columns to eliminate any duplicated records.

### 3. Standardize Text Values
- Inserted new columns next to text fields such as gender and country names.
- Applied formulas:
  - `=UPPER(cell)` to convert text to uppercase,
  - `=LOWER(cell)` to convert to lowercase,
  - `=PROPER(cell)` to capitalize the first letter of each word.
- Used **Paste Special > Values** to replace formulas with text.
- Used **Find & Replace** to correct specific text values (e.g., replacing "usa" with "USA").

### 4. Convert Date Formats
- Selected date columns and applied **Custom Date Format** `dd-mm-yyyy` to standardize date display.

### 5. Rename Column Headers
- Renamed columns for consistency using lowercase letters and underscores instead of spaces (e.g., `release_year`, `date_added`).

### 6. Check and Fix Data Types
- Ensured numeric columns were formatted as **Number**.
- Ensured date columns used **Date** format.
- Ensured text columns were formatted as **Text** or **General**.

## Tools Used

- Microsoft Excel (latest version)

## Notes

- All data cleaning was done using Excel built-in features and formulas.
- No external software or code was used.
- Screenshots of key steps and dataset can be found in the `screenshots` folder.

---

This document summarizes the data cleaning performed to ensure a high-quality dataset for further analysis or use.
