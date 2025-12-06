# Premier League Regression Analysis

This project investigates which performance factors best explain team success in the Premier League.  
Using data from the 2024/2025 season, the study applies multiple linear regression to identify the offensive, defensive, technical, and physical metrics that most strongly predict total points won.

The project showcases skills in data cleaning, exploratory data analysis, statistical modeling, variable selection, and interpretation of econometric results.


## Project Overview

The goal of this analysis is to determine **which measurable team characteristics are most strongly associated with Premier League performance**.  
The project explores questions such as:

- Do offensive metrics (e.g., shots on target, xG) explain points better than defensive ones?  
- Are technical abilities (e.g., pass completion) more important than physical metrics (e.g., distance covered)?  
- Which variables remain significant when controlling for others in a multiple regression model?


## Data

- **Source:** FBref.com  
- **Season:** Premier League 2024/2025  
- **Observations:** 20 teams  
- **Key variables analyzed:**
  - Shots on target (SoT)
  - Expected goals (xG)
  - Pass completion rate (Cmp%)
  - Tackles won (TklW)
  - Defensive errors leading to shots/goals (Err)
  - Total distance covered (TotDist)
  - Other relevant performance metrics


## Methodology

The project uses the following statistical techniques:

### Exploratory Data Analysis  
- Correlation analysis  
- Visual inspection of performance metrics  
- Outlier detection  

### Multiple Linear Regression  
- Modelling points won as the dependent variable  
- Evaluating individual and joint variable significance  
- Checking model assumptions  

### Model Selection & Diagnostics  
- AIC-based variable selection  
- Variance Inflation Factor (VIF) for multicollinearity  
- Residual analysis and model validation  


## Key Findings (High-Level Summary)

- Offensive and technical metrics generally have the strongest explanatory power for team success.  
- Some defensive and physical metrics contribute but are less predictive when controlling for xG and shooting metrics.  
- Models with selected variables outperform full-variable models in terms of explanatory power and statistical significance.

*A full interpretation and discussion are provided in the report.*


