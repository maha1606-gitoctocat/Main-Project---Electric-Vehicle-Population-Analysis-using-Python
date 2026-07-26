**Electric Vehicle (EV) Data Analysis using Python**

A comprehensive Exploratory Data Analysis (EDA) project that uncovers electric vehicle adoption trends, manufacturer performance, geographic distribution, and vehicle characteristics using Python.

**Project Overview**

The rapid growth of Electric Vehicles (EVs) is transforming the automotive industry. This project analyzes an Electric Vehicle registration dataset to understand adoption patterns, identify leading manufacturers and models, evaluate vehicle performance, and generate business insights through data cleaning, feature engineering, statistical analysis, and visualization.

The project demonstrates a complete Data Analytics workflow, from raw data preprocessing to actionable insights.

## Project Objectives

1.	To analyze the distribution of electric vehicles across different geographical regions.
2.	To identify the most popular electric vehicle manufacturers and models based on registration data.
3.	To examine the trends in electric vehicle adoption over different model years.
4.	To compare the performance and characteristics of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).
5.	To analyze the electric driving range of vehicles and identify factors influencing vehicle performance.
6.	To derive meaningful insights from the dataset using data cleaning, exploratory data analysis (EDA), and visualization techniques in Python.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn


## Project Workflow

### Data Cleaning
- Removed duplicate records
- Handled missing values
- Renamed columns
- Converted data types
- Removed unnecessary columns


### Feature Engineering

Created new features including:

- Vehicle Age
- Range Category
- EV Category
- Simplified CAFV Eligibility

### Statistical Analysis

Performed descriptive statistics including:

- Mean
- Median
- Mode
- Variance
- Standard Deviation
- Skewness
- Kurtosis

### Exploratory Data Analysis

### Univariate Analysis

- EV Type Distribution
- Top Counties
- Top Cities
- Top Manufacturers
- Top EV Models
- Electric Range Distribution
- Model Year Distribution
- CAFV Eligibility Distribution

### Bivariate Analysis

- EV Type vs Electric Range
- Manufacturer vs Registration Count
- Model Year vs Electric Range
- CAFV Eligibility vs EV Type

### Multivariate Analysis

- Manufacturer × EV Type × Electric Range
- Heatmap of Manufacturer vs EV Type
- Model Year × EV Type × Registration Count

## Key Insights
- Total Records Analyzed: **1,999** electric vehicle registrations.
- Battery Electric Vehicles (BEVs): **1,567 (78.4%)**
- Plug-in Hybrid Electric Vehicles (PHEVs): **432 (21.6%)**
- Top Manufacturer: **Tesla** with **786** registered vehicles.
- Most Registered EV Model: **Tesla Model Y** with **401** registrations, followed by **Tesla Model 3** with **299** registrations.
- Top County: **King County** with **1,194 EV** registrations.
- Top City: **Seattle** with **338 EV** registrations.
 
**Average Electric Driving Range:**
- BEVs: **60.76 miles**
- PHEVs: **31.81 miles**
  
**CAFV Eligibility Distribution:**
- Eligible: **733**
- Not Eligible: **180**
- Unknown: **1,086**
  
- Highest Registration Year: **2023 with 393** vehicle registrations, indicating rapid growth in EV adoption.
- Highest Average Electric Range by Manufacturer: **Jaguar with 234.0 miles.**

**Top 5 Manufacturers by Registration Count:**
- Tesla – 786
- Nissan – 151
- Chevrolet – 148
- Kia – 125
- BMW – 103

**Top 5 EV Models by Registration Count:**
- Model Y – 401
- Model 3 – 299
- Leaf – 151
- Model S – 70
- Model X – 58


## Visualizations Included

- Count Plots
  
- Bar Charts
  
- Histograms
  
- Box Plots
  
- Scatter Plots
  
- Correlation Heatmap
  
- Pivot Table Heatmap
  
- Grouped Bar Charts

