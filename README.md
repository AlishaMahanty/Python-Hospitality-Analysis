# Python Hospitality Analysis

This repository contains a hospitality data analysis completed while learning and applying Python for data analysis.

The analysis uses Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn to explore the data, clean and transform it, and generate insights through visualizations.

## Overview

The analysis follows these main steps:

1. Data Import
2. Data Exploration
3. Data Cleaning
4. Data Transformation
5. Data Analysis
6. Data Visualization
7. Insight Generation

## Dataset

The analysis uses multiple hospitality datasets covering bookings, hotels, rooms, dates, and aggregated booking information.

The main datasets include:

- `fact_bookings`
- `fact_aggregated_bookings`
- `dim_hotels`
- `dim_rooms`
- `dim_date`

## Python Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## What I Worked On

### 1. Data Import

Imported the hospitality datasets into Pandas DataFrames and examined their structure.

Some of the initial checks included:

- Number of rows and columns
- Column names
- Data types
- Unique values
- Basic statistics

### 2. Data Exploration

Explored the datasets to understand the available information and identify patterns and data-quality issues.

Examples include:

- Exploring booking platforms
- Checking room categories
- Examining booking status
- Reviewing revenue and guest information
- Understanding hotel and room data

### 3. Data Cleaning

Identified and handled data-quality issues found during the analysis.

This included checking:

- Missing or invalid values
- Incorrect data types
- Unusual guest counts
- Revenue outliers
- Date formats

### 4. Data Transformation

Created new columns and transformed the data to support analysis.

For example, occupancy percentage was calculated using successful bookings and available capacity.

I also worked with:

- Date conversion
- Calculated columns
- `groupby()`
- Aggregation
- DataFrame merging
- `apply()`
- `lambda` functions

### 5. Analysis & Visualization

Used Pandas and visualization libraries to analyze different aspects of the hospitality data.

The analysis includes areas such as:

- Occupancy by room category
- Occupancy by city
- Weekday vs. weekend occupancy
- Monthly revenue
- Revenue by city
- Booking platform analysis
- Ratings
- Room categories

Visualizations include:

- Bar charts
- Line charts
- Pie charts

### 6. Insights

The analysis was used to identify patterns and trends in occupancy, revenue, bookings, and other hospitality metrics.

The notebook contains the calculations, visualizations, and observations developed during the analysis.

## Key Learning

Through this analysis, I worked with Python for data analysis and gained hands-on experience with:

- DataFrame operations
- Data exploration
- Data cleaning
- Data transformation
- Data aggregation
- Data merging
- Date handling
- Basic visualization
- Generating insights from data
