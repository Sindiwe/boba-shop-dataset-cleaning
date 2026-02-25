# boba-shop-dataset-cleaning

# Project Overview.

The dataset contained information about boba tea shops in San Francisco and it was intended to support a marketing agency planning a collaboration campaign with top-rated shops within a 10-mile radius of their target area. However, the dataset contained several data quality issues, including duplicate entries, invalid rating values, and improperly structured location data. The goal of this project was to identify dirty data elements, clean and transform the dataset using Google Sheets functions, and prepare it for accurate analysis and decision-making.

# Dataset Source

Original dataset provided as part of the Google Analytics course on Coursera 
through the She Code Africa program.

(Download here:https://docs.google.com/spreadsheets/d/1ETb45bbtIn-q3Z-eps9cw66GgS2Gye8cOfKIoFi65DU/template/preview.)

# Issues Identified
- Duplicate records
- Invalid Yelp ratings (>5)
- Combined latitude & longitude in one column
  
# Cleaning Process
- Removed duplicates using Data Cleanup
- Used COUNTIF to identify invalid ratings
- Corrected ratings outside valid range
- Used the SPLIT function to separate coordinates
- Standardized longitude values

# Outcome
- 604 clean records
- Accurate ratings
- Structured location data ready for mapping and analysis

# Skills Demonstrated
- Data cleaning
- Data validation
- Spreadsheet functions
- Analytical thinking
