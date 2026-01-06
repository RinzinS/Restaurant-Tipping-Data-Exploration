# Restaurent Tipping Behavior in Restaurants: A Data-Driven Exploration

##  Project Summary
This project analyzes **restaurant tipping behavior** using the classic `tips.csv` dataset.  
The study explores how factors such as **gender, smoking status, meal time, and group size** influence tipping amounts, both in raw data and after removing outliers.

Key steps included:
- **Data Cleaning**: Removed duplicates and extreme outliers (e.g., a $16.30 tip on an $11.87 bill) to ensure reliable results.  
- **Exploratory Analysis**: Compared tipping rates across subgroups (male vs female, smoker vs non-smoker, lunch vs dinner, small vs large groups).  
- **Regression Modeling**: Found that **total bill size** is the strongest predictor of tip amount, while demographic and contextual factors had weaker or inconsistent effects.  

### Main Findings
- Women tip a higher **percentage** of their bill than men.  
- Non-smokers tip more generously than smokers.  
- Lunch tips are slightly higher than dinner tips.  
- Smaller groups tip a higher percentage compared to larger groups.  
- Outlier removal clarified true patterns and improved regression accuracy.  

**Conclusion**: The biggest driver of tip size is simply **spending more money on the meal**. Other factors show modest trends but are not statistically significant predictors in the regression model.

---

##  Project Overview
- **Dataset**: 244 rows, 7 columns (after cleaning → 224 rows).
- **Goal**: Identify patterns in tipping behavior and assess how extreme values affect results.
- **Methods**:
  - Data cleaning (duplicate removal, outlier filtering).
  - Exploratory analysis with subgroup comparisons.
  - Regression modeling to identify significant predictors of tip amounts.
- **Key Insight**:  
  The **total bill** is the strongest predictor of tip amount. Other factors (gender, smoking, meal time, group size) show weaker or inconsistent effects.

---

##  Features
- **Data Preparation**: Duplicate removal, creation of new variables (`total_cost`, `tip_pct`, `bill_pct`).
- **Comparisons**:
  - Male vs Female tipping rates
  - Smoker vs Non-Smoker
  - Lunch vs Dinner
  - Small vs Large groups
- **Outlier Handling**: Removal of extreme tip values for clearer visualization and more reliable regression results.
- **Regression Analysis**:  
  - Raw data: $0.092 increase in tip per $1 increase in bill.  
  - Cleaned data: $0.095 increase in tip per $1 increase in bill.

---
