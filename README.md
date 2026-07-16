Aadhaar Enrolment Pattern Analysis 2020–2026

## Overview
Exploratory Data Analysis on Aadhaar enrolment patterns across Indian states and districts, covering 500,000 records, to identify coverage gaps, age-related adoption patterns, and enrolment chronology for policy intervention planning.

## Files

- `analysis.py` — EDA script (data cleaning, standardization, aggregation, 5 visualizations)
- `api_data_aadhaar_enrolment_0_500000.csv` — Dataset (500,000 records)
- `Aadhaar_Enrolment_Pattern_Analysis.pdf` — Full project report

## Tools Used
Python | Pandas | NumPy | Matplotlib | Power BI

## Key Findings

- Top 10 states account for a disproportionately large share of total enrolments
- Union territories and northeast states are underrepresented in coverage
- Adults (18+) consistently make up 60–75% of enrolments across all states
- Children aged 0–5 are the most underrepresented age group nationwide
- District rankings don't always match state rankings — local factors drive enrolment success
- National enrolment activity shows clear monthly/seasonal variation

## Data Cleaning & Standardization

- 500,000 initial records → 493,964 after duplicate removal
- 15+ state name variations standardized (misspellings, case mismatches, outdated names like Orissa → Odisha)
- Date parsing with error coercion; invalid entries filtered via regex
