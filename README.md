📊 Crime Data Analysis & Cleaning

📌 Overview

This project focuses on cleaning, exploring, and analyzing large-scale crime data (2020–Present) using Python. The goal was to transform raw, noisy data into a clean analytical dataset and uncover temporal, regional, and categorical crime patterns through exploratory data analysis (EDA). 

FDA_Project1_Report

🎯 Objectives

Clean and standardize a large real-world crime dataset

Handle missing values, outliers, and data type inconsistencies

Perform exploratory data analysis to identify trends and patterns

Visualize crime distribution across time, location, and categories

Derive insights that could support predictive crime analytics

🛠️ Tools & Technologies

Programming Language: Python

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Techniques: Data Cleaning, EDA, Feature Engineering, Scaling

Environment: Jupyter Notebook

🧹 Data Cleaning Process

Verified dataset structure using df.info() and df.describe()

Checked and confirmed absence of duplicate records

Handled missing values using mean/median (numerical) and “Unknown” (categorical)

Converted report dates into datetime format and extracted year, month, and weekday

Detected outliers using IQR method and boxplots

Encoded categorical variables and standardized numerical features

📈 Exploratory Data Analysis (EDA)

The following analyses were performed:

Crime Trends Over Time: Year-wise crime trends from 2020 onward

Seasonality Analysis: Monthly crime distribution highlighting seasonal effects

Top Crime Types: Identification of most frequently reported crimes

Regional Analysis: Comparison of crime counts across locations

Day-of-Week Patterns: Analysis of crime frequency by weekday

🔍 Key Insights

Crime levels fluctuate yearly with noticeable dips during pandemic years

Higher crime frequency observed during warmer months

A small set of crime types accounts for a majority of incidents

Certain regions consistently report higher crime volumes

Crimes tend to peak on weekends, aligning with social activity patterns

## 🖥️ Visual Highlights

### Crime Trends Over Time
![Crime Trends](images/crime_trends.png)

### Top Crime Types
![Top Crimes](images/top_crimes.png)

### Regional Crime Distribution
![Regional Crime](images/regional_crime.png)
