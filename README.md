# YuvaIntern Week 1 – R Data Analysis

## Project Title
Data Cleaning and Preliminary Analysis with R

## Dataset
New York Air Quality Measurements (`airquality`), May–September 1973.

## Objective
This project demonstrates a reproducible R workflow for:
- Data inspection and quality checks
- Missing-value analysis and imputation
- Categorical encoding
- Outlier identification using the IQR method
- Numeric normalization
- Descriptive statistics
- Correlation analysis
- Exploratory visualizations

## Dataset Source
Official R documentation:
https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/airquality.html

## Main Findings
The analysis identifies missing values in Ozone and Solar.R, converts Month into a categorical factor, and prepares standardized numeric variables. Preliminary correlations show a positive association between ozone and temperature and a negative association between ozone and wind speed. These are descriptive associations and do not establish causation.

## Reproducibility
The script uses the built-in R `airquality` dataset, so no external dataset download is required. Open the `.R` file in R/RStudio and run the commands sequentially.
