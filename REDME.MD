# BITS Digital Grading Console

## Project Overview

The BITS Digital Grading Console is a browser-based grading application developed for the BITS Digital CodeForge Challenge.

The application allows instructors to:

- Upload student marks from Excel
- Select a course
- Configure grade ranges
- Calculate student grades
- View class statistics
- Visualize grade distribution
- Export grading results

## Input Format

The Excel input file must contain exactly these columns:

- BITS ID
- Course
- Total Marks

Total Marks should be a whole number between 0 and 100.

## Grade Ranges

| Grade | Marks |
|---|---|
| A | 80–100 |
| A- | 70–79 |
| B | 60–69 |
| B- | 50–59 |
| C | 40–49 |
| C- | 30–39 |
| D | 20–29 |
| E | 0–19 |

## Bug Fixes

The application was reviewed and multiple intentional bugs were identified and fixed, including:

- Duplicate course options
- Incorrect Excel file acceptance
- Reversed Min/Max statistics
- Empty-data handling
- Invalid marks validation
- Valid 100–100 grade range handling
- Bell curve division-by-zero issue
- Safer CSV export

Detailed information is available in:

`BITS_Digital_CodeForge_Submission.xlsx`

## Enhancements

The reimagined application includes:

1. Excel input validation
2. Duplicate-free course selection
3. Class-size and grade-distribution summary
4. Safer finalization and export
5. Improved empty-state handling

## How to Run

Open the deployed GitHub Pages URL in a browser.

Upload an Excel file following the required format, select the course, configure the grade ranges if required, and generate the grading results.

## Technology

- HTML
- CSS
- JavaScript
- SheetJS/XLSX
- GitHub Pages

## Submission

This repository contains the application and the supporting Bug Fix Log / enhancement documentation for the BITS Digital CodeForge Challenge.
