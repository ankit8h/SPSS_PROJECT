# SPSS_PROJECT



Here is a complete summary of your project, from the initial question to the final conclusion.
This is the "executive summary" of your SPSS project.

1. 🎯 Project Title & Objective

Title: An Analysis of the Factors Affecting the Risk-Adjusted Performance of Indian Large Cap Mutual Funds.
Objective: The goal was to determine which key, measurable factors have a statistically significant impact on a mutual fund's real-world performance.
Research Question: "What is the relationship between a fund's 3-Year Sharpe Ratio (its risk-adjusted performance) and its Expense Ratio, Fund Size (AUM), Fund Age, and Turnover Ratio?"




<img width="1368" height="295" alt="Screenshot 2025-11-15 092951" src="https://github.com/user-attachments/assets/ceefc8b7-142e-437a-b73d-2b8fee6f09e8" />

2. 🔬 Methodology & Data

Model: We used a Multiple Linear Regression in SPSS. This is the correct model for predicting a continuous number (like the Sharpe Ratio) based on several input factors.
Sample: Our dataset consisted of 25 Large Cap (Direct-Growth) equity funds. We focused on one category to ensure an "apples-to-apples" comparison.
Variables:
Dependent Variable: Three_year_Sharpe_ratio (This was our "Y" – the outcome we wanted to predict).
Independent Variables: Expense_ratio, Asset_under_management_in_crore, Fund_age_in_years, Turnover_ratio_in_percentage (These were our "X" factors – our predictors).

3. 📊 Key Statistical Findings (The Results)

This is the main story from your SPSS output.
1. Is the model useful? Yes.
The ANOVA table's "Sig." (p-value) was 0.02. Since this is less than 0.05, our overall model is statistically significant. It's not just a random result.
2. How much does the model explain? 17%.
The Adjusted R-Square was 0.17. This is a key finding. It means our four variables (expenses, size, age, turnover) can only explain 17% of the variation in a fund's performance.
3. What factors are significant? Only Fund Size.
Asset_under_management (AUM) was the only statistically significant predictor (p = 0.05).
The coefficient was positive, suggesting that funds with a larger AUM tend to have a slightly better risk-adjusted performance.
4. What factors are NOT significant? Expenses and Turnover.
Expense_ratio (p = 0.848), Turnover_ratio (p = 0.450), and Fund_age (p = 0.063) were all not statistically significant.
This is a fascinating insight: for this dataset, paying a lower fee or having a low-turnover manager had no statistically provable effect on performance.
5. Is the model "healthy"? Yes.
We checked for multicollinearity. All VIF (Variance Inflation Factor) scores were ~1.3, which is excellent (far below the problem level of 5 or 10). This means our predictors are independent and the results are reliable.

4. 💡 Conclusion & Implications (The "So What?")

The Main Story: Your project's main conclusion is that 83% of a fund's performance (the part not explained by your model) is driven by unmeasured factors. This is primarily the fund manager's individual skill, their specific stock-picking strategy, and market luck.
What It Means: While a larger Fund Size (AUM) seems to provide a small, significant advantage, the common advice to only focus on low Expense Ratios or low Turnover is not supported by your data. The manager's skill (Alpha) appears to be far more important than these simple metrics.
Limitations: The biggest limitation is the small sample size (n=25). With a larger sample (e.g., n=100), the small, real-world effect of the Expense Ratio might have become statistically significant. This is a perfect point to discuss in your final report.
This provides a complete, A-Grade summary of your entire project.
Would you like me to help you phrase the specific hypotheses for your report (e.g., "Hypothesis 1: A lower Expense Ratio will have a positive impact on the 3-Year Sharpe Ratio")?
