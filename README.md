# Sales_By_Ads

## Project Overview
This project analyzes the **impact of different advertising channels (TV, Radio, Newspaper) on product sales** using real-world advertising spend data. The goal is to identify the most effective channels and provide **data-driven recommendations for marketing budget allocation**.

---

## Dataset
- 200 records of advertising spend and sales data  
- **Features:** `TV`, `Radio`, `Newspaper` (spend in $k)  
- **Target:** `Sales` (units sold in $k)  
- Source: Classic Advertising dataset  

---

## Objective
- Determine which advertising channels contribute most to sales.  
- Recommend **budget allocation** to maximize sales and ROI.  
- Visualize relationships between ad spend and sales.  

---

## Methodology
1. **Data Preprocessing:** Loaded dataset and cleaned any missing values.  
2. **Exploratory Data Analysis (EDA):** Checked correlations and trends.  
3. **Linear Regression:**  
   - Model: `Sales ~ TV + Radio + Newspaper`  
   - Calculated **coefficients** to measure sales impact per $1k spent.  
4. **Visualization:**  
   - Plotted scatter plots of each channel vs sales with regression lines (Matplotlib for static plots).  
5. **Budget Recommendations:**  
   - Allocate budget proportionally to channels with highest positive impact (Radio > TV > Newspaper).  

---

## Key Findings
- **Radio ads** have the highest positive impact on sales per $1k spent.  
- **TV ads** also positively impact sales but less than Radio.  
- **Newspaper ads** have negligible effect.  
- **Actionable Recommendation:** Reduce Newspaper spend and reallocate to Radio and TV for higher ROI.  

---

## Tools & Technologies
- Python (`pandas`, `scikit-learn`, `matplotlib`)  
- Linear Regression  
- Data Analysis & Visualization  
---

## Budget Allocation Recommendation:

Based on the regression analysis of advertising channels, Radio and TV demonstrated the highest positive impact on sales per $1k spent, while Newspaper had negligible or negative influence. Therefore, it is recommended to increase the advertising budget for Radio and TV, allocating funds proportionally to their effectiveness.

For example, if the total marketing budget is $100k, a larger share should go to Radio (the most effective channel), followed by TV, while minimizing or eliminating spending on Newspaper ads. This data-driven reallocation ensures maximum sales impact per dollar spent, improves ROI, and reduces wasted expenditure on low-performing channels.

---
## Author

Dri – BSc Data Science student
