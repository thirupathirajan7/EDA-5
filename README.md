# Healthcare Data Understanding, Cleaning & Exploratory Analysis

## Project Overview

This project focuses on understanding, cleaning, transforming, and analyzing healthcare data. The dataset contains information about patient admissions, medical conditions, billing amounts, admission dates, discharge dates, and patient demographics.

## Objectives

- Clean missing values in the healthcare dataset
- Standardize date attributes
- Categorize admissions by urgency
- Calculate summary statistics for billing amounts
- Calculate hospital stay duration in days
- Segment demographics by medical condition

## Technologies Used

- Python
- Pandas
- Jupyter Notebook
- Matplotlib
- Seaborn

## Data Cleaning and Analysis

### 1. Missing Value Cleaning
Missing values were identified and cleaned to improve data quality. Missing medical codes were handled by assigning an `Unknown` category where required.

### 2. Date Standardization
Admission and discharge dates were converted into a standardized datetime format using Pandas.

### 3. Admission Urgency Categorization
Admission types were categorized into three groups:

- Emergency
- Elective
- Urgent

The `routine` admission type was categorized as `Elective` for the required analysis.

### 4. Billing Amount Analysis
Summary statistics were calculated for billing amounts, including count, mean, standard deviation, minimum, maximum, and quartiles.

### 5. Hospital Stay Analysis
Hospital stay duration was calculated using the admission date and discharge date. Summary statistics were then calculated for the hospital stay duration.

### 6. Demographic Analysis
Patient demographics were analyzed based on medical conditions, including the average age for each medical condition.

## Admission Category Summary

| Admission Category | Count |
|---------------------|------:|
| Elective            | 196   |
| Emergency           | 188   |
| Urgent              | 116   |

## Project Structure

Healthcare-Data-Analysis/
- Healthcare_EDA_Task_5.ipynb
- README.md

## Conclusion

The healthcare dataset was successfully cleaned and transformed for analysis. Missing values were handled, date attributes were standardized, admission types were categorized, and statistical analysis was performed on billing amounts, hospital stay duration, and patient demographics.

This project demonstrates the use of Python and Pandas for healthcare data cleaning, transformation, and exploratory analysis.
