# Marketing Campaign Analysis

## Project Overview

This project explores the response patterns in a marketing campaign to understand which customer segments are more likely to engage. Through exploratory data analysis (EDA), we uncover trends and make recommendations to guide future campaign strategies.

---

## Goal

To help businesses increase marketing effectiveness by identifying customer characteristics that lead to successful campaign outcomes.

---

## Features

- Analysis of customer demographics and behavior
- Visualization of response rates across age, education, job, and past campaign success
- Identification of key drivers for positive responses
- Clear recommendations for future campaign targeting

---

## Data

- **Source**: Kaggle
- **Size**: 200,000 records with 17 attributes

---

## Tools Used

- Python
- Jupyter Notebook
- Pandas, Seaborn, Matplotlib

---

## 🧭 Project Process

Here’s a breakdown of the step-by-step process followed:

### 1. Data Loading & Overview
- Loaded the dataset into a Pandas DataFrame
- Inspected structure, column types, and null values

### 2. Target Variable Exploration
- Counted values of the `y` column (response: yes/no)
- Visualized distribution to detect class imbalance

### 3. Demographic Analysis
- Plotted response rate by:
  - Age group
  - Job title
  - Marital status
  - Education level

### 4. Past Campaign Impact
- Analyzed the effect of `poutcome` (previous outcome) on current response
- Found strong correlation between past success and current response

### 5. Economic Variables
- Explored account balance and other financial indicators
- Checked their influence on customer behavior

### 6. Summary of Key Patterns
- Combined insights across all variables
- Identified top traits of likely responders

### 7. Recommendations
- Based on insights on data to provide practical targeting advice for future campaigns

---

## Key Results & Insights

- Customers aged **30–40** showed higher likelihood of engagement
- Positive past campaign outcomes (`poutcome = success`) correlated strongly with future response
- Response rates were lowest among customers with unknown job/education status
- Overall response rate was low (imbalanced data)

---

## Recommendations

- Focus campaigns on **middle-aged customers** with prior positive engagement
- Clean up missing/unknown demographic data
- Consider a predictive model to classify customers for future outreach

---

## 🧭 Project Process

The project followed a structured exploratory data analysis (EDA) process:

1. Importing Libraries  
2. Loading the Dataset  
3. Data Inspection  
4. Data Cleaning  
5. Exploring the Target Variable (`y`)  
6. Visualizing Campaign Responses  
7. Analyzing Demographic Features (Age, Job, Marital, Education)  
8. Exploring Past Campaign Outcomes (`poutcome`)

---

## 🧠 Key Takeaways

- Customers with past campaign success (`poutcome = success`) are much more likely to say "yes" again
- Most customers responded "no" — indicating strong class imbalance
- Demographics like job, education, and marital status show minor variations but aren't strong predictors alone

Check out the notebook [**here**](https://github.com/theo-seun/marketing-campaign-analysis/blob/main/Marketing%20Campaign.ipynb)



