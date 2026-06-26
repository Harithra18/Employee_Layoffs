# Tech Industry Layoffs Analysis — Python Project

## Overview
Performed Exploratory Data Analysis (EDA) on a tech industry layoffs 
dataset to identify layoff patterns, detect outliers, and classify 
companies by risk level using Python.

## Tools & Technologies
- Python (Google Colab)
- Pandas & NumPy — Data cleaning, preprocessing, null handling
- Matplotlib & Seaborn — Data visualisation
- IQR Method — Outlier detection and treatment

## Key Analysis Performed
- Loaded and explored layoffs dataset (shape, columns, null values)
- Handled missing values in total_laid_off and percentage_laid_off
- Detected outliers using IQR (Interquartile Range) method
- Classified companies into Low / Normal / High risk levels based 
  on layoff numbers
- Visualised layoff distribution by risk level using Seaborn boxplot
- Removed outliers using clipping method for clean analysis
- Exported final cleaned dataset as cleanedlayoffs_data.csv

## Project Files
- `layoffs.ipynb` — Complete Python analysis notebook
- `cleanedlayoffs_data.csv` — Cleaned output dataset

## Dataset
Tech industry layoffs data containing company-wise layoff numbers 
and percentage of workforce laid off

## Skills Demonstrated
Python · Pandas · NumPy · Matplotlib · Seaborn · EDA · 
Data Cleaning · Outlier Detection · Statistical Analysis · 
Risk Classification
