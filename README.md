# House Price Statistics Analysis

A comprehensive statistical analysis project applying core statistics concepts to a house price dataset. This repository demonstrates practical applications of statistical methods including descriptive statistics, distributions, hypothesis testing, and correlation analysis.

## 📋 Overview

This project analyzes a house price dataset containing 4,600 property records with 18 features including price, bedrooms, bathrooms, square footage, and location information. The analysis covers fundamental to advanced statistical concepts with visual representations and numerical insights.

## 🎯 Topics Covered

1. **Raw Data Exploration** - Initial dataset investigation and structure
2. **Frequency Distribution & Histograms** - Distribution patterns of house prices
3. **Cumulative Frequency Distribution** - Cumulative analysis of price data
4. **Measures of Central Tendency** - Mean, median, and mode calculations
5. **Measures of Dispersion** - Understanding data spread and variability
6. **Range, IQR, Standard Deviation, Coefficient of Variation** - Advanced spread metrics
7. **Normal Distribution** - Analyzing normality and distribution fitting
8. **Five Number Summary** - Quartile and percentile analysis
9. **Boxplots** - Visual representation of data distribution and outliers
10. **Scatter Plot** - Relationship analysis between variables
11. **Scatter Plot Matrix** - Multi-variable relationship visualization
12. **Z-Scores** - Standardization and outlier detection
13. **Probability Concepts** - Fundamental probability applications
14. **Correlation Analysis** - Measuring relationships between variables
15. **Hypothesis Testing (T-test)** - Statistical significance testing

## 📊 Dataset Information

- **Total Records**: 4,600 houses
- **Total Features**: 18
- **Data Types**: Numerical and categorical
- **Missing Values**: None

### Key Features

| Feature | Type | Description |
|---------|------|-------------|
| price | float | House price |
| bedrooms | float | Number of bedrooms |
| bathrooms | float | Number of bathrooms |
| sqft_living | int | Living space (sq ft) |
| sqft_lot | int | Lot size (sq ft) |
| floors | float | Number of floors |
| waterfront | int | Waterfront property (0/1) |
| view | int | View rating (0-4) |
| condition | int | Property condition (1-5) |
| sqft_above | int | Above-ground space (sq ft) |
| sqft_basement | int | Basement space (sq ft) |
| yr_built | int | Year built |
| yr_renovated | int | Year renovated |
| street | str | Street address |
| city | str | City |
| statezip | str | State and zip code |
| country | str | Country |
| date | str | Sale date |

### Descriptive Statistics

- **Price Mean**: $551,962.99
- **Price Median**: $460,943.46
- **Price Range**: $0 - $26,590,000
- **Average Bedrooms**: 3.4
- **Average Bathrooms**: 2.16
- **Average Living Space**: 2,139.35 sq ft
- **Average Year Built**: 1970.79

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib scipy
