# Customer Subscription Analysis — End-to-End EDA Project

## Project Overview
This project performs a complete exploratory data analysis (EDA) on a bank marketing dataset to understand customer behavior and identify factors influencing subscription to term deposit campaigns. The workflow follows a structured data analytics pipeline from raw data inspection to statistical testing and final business insights.

---

## Objective
Analyze customer demographics, financial attributes, and campaign interactions to determine patterns that affect subscription decisions and generate actionable business recommendations.

---

## Dataset Information
- Records: 45,211 customers  
- Features: 17 columns  
- Type: Structured tabular dataset  
- Target Variable: **y (Subscription: Yes/No)**

### Feature Categories
**Demographic:** age, job, marital, education  
**Financial:** balance, default, housing, loan  
**Campaign:** contact, duration, campaign, pdays, previous, month  
**Target:** subscription outcome

---

## Project Workflow

### Day 1 — Data Understanding
- Inspected structure and datatypes
- Checked missing values and duplicates
- Identified placeholder values ("unknown")
- Logged data quality issues

---

### Day 2 — Data Cleaning & Preprocessing
- Standardized categorical text formatting
- Replaced placeholder values
- Removed duplicates
- Detected outliers using IQR method
- Applied log transformation to skewed variables
- Validated dataset integrity

---

### Day 3 — Exploratory Data Analysis
Performed univariate and bivariate analysis:

**Univariate**
- Age distribution
- Call duration distribution
- Job frequency distribution

**Bivariate**
- Age vs Balance relationship
- Balance variation across job categories
- Correlation heatmap

**Segment Analysis**
- Customer segmentation by age group
- Subscription behavior comparison

---

### Day 4 — Statistical Testing & Feature Engineering
Performed hypothesis testing:

- **T-Test:** Balance differs significantly between subscribers and non-subscribers
- **ANOVA:** Balance varies across job categories
- **Chi-Square:** Education level affects subscription outcome

Created engineered features:
- Age Group
- Balance Level
- Campaign Intensity
- Contact History Flag
- Risk Profile

Generated final processed dataset.

---

## Key Insights
- Middle-aged customers show highest subscription likelihood.
- Job category influences financial capacity.
- Education level significantly impacts decision behavior.
- Customer responses vary by campaign timing.
- Numerical features show low correlation, indicating decisions depend on multiple factors.

---

## Strategic Recommendations
- Target middle-aged working professionals for campaigns.
- Focus marketing efforts on high-balance segments.
- Schedule campaigns during high-response months.
- Reduce calls to low-probability segments.
- Use engineered segmentation features for targeting.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## Repository Structure
