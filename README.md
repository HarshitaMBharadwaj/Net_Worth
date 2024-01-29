# NBA Player Salary 

## Background
In the competitive landscape of professional basketball, player salaries in the NBA are subject to scrutiny. This study employs sports analytics to construct a Salary Efficiency Index (SEI) that evaluates the correlation between player performance and salaries, aiming to enhance player valuation and inform salary negotiations.

## Objective
The primary goal is to develop a predictive model using NBA player statistics from 2015 onwards to calculate SEI, providing insights into player valuation and aiding team management decisions.

## Research Question
How can NBA player statistics be used to construct SEI, assessing the relationship between on-court performance and salaries? How does SEI identify potential overpaid or underpaid players and illuminate instances of overperformance or underperformance relative to earnings?

## Data Acquisition
Player statistics were obtained from the API-NBA, while player salaries were sourced from HoopsHype via web scraping techniques. The collected data was cleansed, structured, and merged for analysis.

## Data Preprocessing
Preprocessing involved cleaning player statistics and salaries, aggregating data, and merging datasets. Statistical columns were converted, missing values were handled, and data integrity was ensured.

## Data Analysis
Descriptive statistics provided insights into player performance metrics and salaries. Distributions highlighted disparities in performance and compensation. Bivariate analysis revealed correlations between performance metrics and salaries.

## Predictive Modelling
Linear Regression, Random Forest, XGBoost, and Neural Network models were developed and evaluated for their predictive capabilities.

## Summary of Model Performances
Random Forest, XGBoost, and Neural Network models outperformed Linear Regression in predicting player salaries, with Random Forest achieving the highest R2 score and lowest MSE.

## Results and Analysis of SEI
SEI was calculated using predicted salaries from the top-performing models, identifying both undervalued and overvalued players based on their on-court contributions.

## Conclusion
The SEI provides a data-driven approach to player valuation, aiding decision-making in salary negotiations and team management. While SEI offers valuable insights, it should be considered alongside other factors in player evaluation.

For further details, refer to the full report.

