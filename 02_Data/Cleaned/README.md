# Cleaned Data

This folder contains validated and cleaned datasets prepared for analysis.

## Purpose

The cleaned dataset is created from the original raw source dataset after performing:

- Data quality checks
- Data type validation
- Missing value checks
- Duplicate checks
- Date validation
- Numeric field validation
- Standardization of categorical fields
- Business-rule validation

## Data Integrity Rule

The original raw dataset is preserved separately and must not be modified.

All cleaning and transformation activities are performed on a separate copy of the raw data.

## Expected Output

The final cleaned dataset will be stored as:

`01_cleaned_data.csv`

## Workflow

Raw Data → Quality Checks → Cleaning → Validation → Cleaned Dataset → Analysis
