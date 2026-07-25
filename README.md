# Statistical Business Analysis

## Project Overview
A comprehensive statistical analysis of business sales data, 
including descriptive statistics, hypothesis testing, correlation 
analysis, confidence intervals, and regression analysis.

## Objectives
- Calculate descriptive statistics for business metrics
- Test hypotheses about regional sales differences
- Analyze correlation between quantity and sales
- Calculate confidence intervals for key metrics
- Perform regression analysis to understand relationships

## Setup & Installation
1. Install Python 3.x
2. Install required libraries:
pip install pandas numpy scipy matplotlib seaborn
3. Clone this repository
4. Open `statistical_analysis.ipynb` in Jupyter/VS Code
5. Run all cells in order

## Project Structure
- `statistical_analysis.ipynb` — main analysis notebook
- `data/` — contains business_data.csv
- `visualizations/` — contains generated charts
- `hypothesis_tests_results.txt` — summary of all test results
- `statistical_report.pdf` — final report with insights

## Technical Approach

### Descriptive Statistics
Calculated mean, median, mode, standard deviation, and variance 
for Total Sales.

### Hypothesis Testing (3 Tests)
1. **T-Test** — Compared North vs South region sales
2. **ANOVA** — Compared sales across all regions
3. **Correlation Test** — Tested significance of Quantity-Sales relationship

### Confidence Interval
Calculated 95% confidence interval for average sales using 
t-distribution.

### Regression Analysis
Performed linear regression to model relationship between 
Quantity and Total Sales.

## Key Findings
- Average Sales: ₹123,650.48 (95% CI: ₹103,776 - ₹143,524)
- No significant difference in sales across regions (p = 0.0972)
- Significant correlation between Quantity and Sales (r = 0.69)
- Regression shows Quantity explains ~47% of sales variation

## Business Insights
1. Sales strategies don't need major regional customization
2. Focusing on quantity/volume can meaningfully drive sales
3. Other factors (beyond quantity) account for over half of 
   sales variation — worth investigating (e.g., product type, pricing)

## What I Learned
- How to perform and interpret hypothesis tests (t-test, ANOVA)
- Understanding p-values and statistical significance
- Calculating and interpreting confidence intervals
- Linear regression and R-squared interpretation
- Translating statistical results into business recommendations