Premier League Performance Drivers

A Multiple Regression Analysis of Team Success (2024/2025 Season)
Objective

What truly drives team success in the Premier League?

This project analyzes which measurable performance indicators best explain total league points during the 2024/2025 season. Using multiple linear regression, the study evaluates the relative importance of offensive, defensive, technical, and physical metrics.

The goal is not only statistical explanation — but identifying actionable performance drivers.

Data

Source: FBref.com

Season: 2024/2025

Observations: 20 Premier League teams

Key Variables

Shots on Target (SoT)

Expected Goals (xG)

Pass Completion % (Cmp%)

Tackles Won (TklW)

Defensive Errors (Err)

Total Distance Covered (TotDist)

Additional performance metrics

Methodology
1️⃣ Exploratory Data Analysis

Distribution analysis

Correlation matrix

Outlier detection

Pairwise performance comparisons

2️⃣ Multiple Linear Regression

Dependent variable: Total Points

Stepwise model specification

Joint and individual hypothesis testing

3️⃣ Model Diagnostics

AIC-based model selection

Variance Inflation Factor (VIF) for multicollinearity

Residual diagnostics

Assumption testing

Results

Offensive metrics (especially xG and Shots on Target) show the strongest and most consistent statistical significance.

Defensive errors negatively impact points but lose significance when controlling for attacking strength.

Physical metrics (e.g., total distance covered) have limited explanatory power.

The selected model improves explanatory efficiency compared to the full model.

(Add R², adjusted R² and p-values here — this is important.)

Key Insight

Premier League performance is primarily driven by attacking efficiency rather than physical intensity or raw defensive volume.

Once attacking quality (xG, shot efficiency) is controlled for, many commonly cited performance indicators lose explanatory power.

Business / Strategic Interpretation

For football clubs and analysts:

Investing in chance creation quality (xG generation) yields stronger performance impact than focusing solely on physical workload metrics.

Technical efficiency plays a larger role than raw activity volume.

Recruitment and tactical strategy should prioritize attacking output metrics.

Repository Structure

R code/ → Data preparation, regression modelling, diagnostics

Premier league regression analysis.pdf → Full statistical report
