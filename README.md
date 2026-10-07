# NYC Yellow Taxi Data Analysis

## Project Overview

This project analyzes NYC Yellow Taxi trip data using Python to understand trip patterns, travel behavior, data quality, and operational trends.

The analysis covers data cleaning, exploratory data analysis, statistical analysis, feature engineering, visualization, and business-oriented insights.

## Dataset

- Dataset: NYC Yellow Taxi Trip Data — January 2025
- Original records: 3,475,226
- Final records after cleaning: 3,472,251
- Records removed: 2,975
- Data retained: 99.91%

The original Parquet dataset is not included in this repository because of its large size.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Analysis Performed

### Data Quality & Cleaning
- Checked missing values and duplicates
- Validated trip duration and distance
- Investigated passenger-count anomalies
- Investigated categorical inconsistencies
- Identified logically impossible records
- Removed clearly corrupted records while retaining legitimate extreme values

### Feature Engineering
Created features including:

- Trip duration in minutes
- Average speed in mph
- Pickup date
- Pickup hour
- Day of week
- Weekend indicator
- Route
- Distance category
- Duration category

### Statistical Analysis

Calculated:

- Mean, median, variance, and standard deviation
- Percentiles
- Interquartile ranges
- Correlations between numerical variables

## Key Findings

- The median trip distance was **1.67 miles**.
- The median trip duration was **11.7 minutes**.
- The average trip duration was **15.03 minutes**.
- The average trip speed was approximately **11.07 mph**.
- **6 PM** was the busiest hour with approximately **267,710 trips**.
- **Thursday** was the busiest day with **613,687 trips**.
- The most common passenger count was **1**.
- Trip distance and duration showed a moderate positive correlation of approximately **0.35**.
- Trip distance and average speed showed a stronger positive correlation of approximately **0.73**.
- More than **30 analytical visualizations** were created to examine temporal, trip, payment, vendor, rate-code, location, and route patterns.

## Data Cleaning Summary

The cleaning process removed records with clearly invalid or corrupted values, including:

- Negative or zero-duration trips
- Trips exceeding 24 hours
- Extremely unrealistic trip distances
- Physically implausible average speeds

Legitimate zero-distance trips, missing values, and unusual but potentially valid records were investigated rather than automatically removed.

## Repository Contents

- NYC_Taxi_Data_Analysis_Sheshank_Kumar_Final.ipynb — Complete analysis notebook
- NYC_Taxi_Data_Analysis_Sheshank_Kumar_Report.pdf — Final project report
- README.md — Project documentation
- .gitignore — Files excluded from version control

## Conclusion

The analysis demonstrates an end-to-end workflow for working with a large real-world transportation dataset, from data-quality assessment and cleaning to statistical analysis, visualization, and interpretation of operational patterns.

## Author

**Sheshank Kumar**

B.Tech — Computer Science & Engineering
