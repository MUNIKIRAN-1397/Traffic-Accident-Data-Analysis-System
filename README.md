# Traffic Accident Data Analysis System

## Project Overview

The Traffic Accident Data Analysis System is a Data Analysis Essentials project focused on inspecting, cleaning, and preprocessing traffic accident data.

## Problem Statement

Traffic accident datasets may contain duplicate records and missing values. Proper data inspection, cleaning, and preprocessing are required before performing further analysis.

## Objectives

- Load and inspect the traffic accident dataset
- Identify missing values and duplicate records
- Clean the dataset
- Handle missing values using appropriate techniques
- Apply feature scaling and standardization
- Perform label encoding and one-hot encoding
- Prepare the dataset for further analysis

## Dataset

- **Raw Records:** 3,024
- **Columns:** 12
- **Domain:** Road Safety / Transportation
- **Target Variable:** Accident Severity
- **Severity Classes:** Minor, Serious, Fatal

## Tools & Technologies

- Python
- NumPy
- Pandas
- Scikit-learn
- Google Colab

## Project Workflow

1. Data Loading
2. Data Inspection
3. Data Cleaning
4. Data Preprocessing

## Data Cleaning

The dataset contained:

- 24 duplicate records
- 50 missing values

Missing values were handled using:

- **Mode** → Categorical columns
- **Median** → Numerical columns

After cleaning:

- **Rows:** 3,000
- **Missing Values:** 0
- **Duplicate Rows:** 0

## Data Preprocessing

The following preprocessing techniques were applied:

### Feature Scaling
Min-Max Scaling was applied to the Speed Limit column.

### Feature Standardization
Standardization was applied to Number of Casualties and Number of Fatalities.

### Label Encoding
Accident Severity was converted into numerical labels.

### One-Hot Encoding
Vehicle Type was converted into separate binary columns.

## Repository Structure

```text
Traffic-Accident-Data-Analysis-System/
│
├── data/
│   └── traffic_accidents_raw.csv
│
├── docs/
│   ├── Traffic_Accident_Review_1.pptx
│   └── Traffic_Accident_Review_2.pptx
│
├── notebooks/
│   └── Traffic_Accident_Data_Analysis.ipynb
│
├── src/
│
└── README.md
