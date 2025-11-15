# Regression Analysis of Indian large Cap Mutual Funds

**Step 1**: **Data Structure and Variable Setup in SPSS**

The initial phase involved meticulously defining the dataset's structure within the SPSS "Variable View."

The setup was implemented as follows:
All variables designated for the analysis (including Fund_names, Three_year_Sharpe_ratio, and Expense_ratio) were uniformly defined as "Numeric" data types.
The "Fund_names" variable was categorized as "Nominal," and Value Labels were applied (e.g., 1.00 assigned to "ICICI PRUDENTIAL LARGE CAP FUNDS") to facilitate the identification of each distinct fund.
Every other variable intended for the subsequent regression analysis was set to the "Scale" measure.

<img width="830" height="160" alt="image" src="https://github.com/user-attachments/assets/badc96ef-6545-444c-bbdc-a6bcf210f42e" />





**Step 2**: **Data Entry**
With the variables defined, the collected data for the 25 Large Cap funds was entered into the "Data View." Each row represents a single fund (a "case"), and each column represents one of the variables. Step 2: Data Entry and Structuring

Following variable definition, the collected empirical data for the 25 Large Cap mutual funds was systematically entered into the statistical software's "Data View."

This structured process is essential for rigorous statistical analysis. The "Data View" was configured as a matrix:
Rows as Cases: Each row represented a single fund (the observation unit).
Columns as Variables: Each column was reserved for a single metric (e.g., 3-Year Annualized Return).
<img width="831" height="563" alt="image" src="https://github.com/user-attachments/assets/99029c88-dbec-4ac5-af93-569ec21e6fc5" />
<img width="829" height="568" alt="image" src="https://github.com/user-attachments/assets/207a40c3-8368-445e-8dab-2886b2ee4125" />





**Step 3:** **Model Specification (Linear Regression)**

The core analysis utilized Multiple Linear Regression (accessible via Analyze > Regression > Linear...). The variables were defined as follows:
Dependent Variable: Three_year_Sharpe_ratio
Independent Variables (Predictors):
Expense_ratio
Asset_under_management_in_crore
Fund_age_in_years
Turnover_ratio_in_percentage

<img width="664" height="546" alt="image" src="https://github.com/user-attachments/assets/a9dffae9-b6a3-4f28-bd74-57e088415aeb" />





**Step 4**: **Output & Interpretation**
After running the analysis, the SPSS Output Viewer generated the key tables. These tables provided the complete statistical findings for the project:
Model Summary: Showed the Adjusted R-Square (0.17), indicating the model's explanatory power.
ANOVA: Showed the overall model's significance (p = 0.02).
Coefficients: Provided the p-values for each individual predictor (identifying AUM as significant) and the VIF scores (confirming no multicollinearity).

<img width="807" height="433" alt="image" src="https://github.com/user-attachments/assets/1fbe7771-2a6f-4663-bf38-88d9089e9f78" />

**Interpretation**

The objective of this study was to identify the key factors influencing the three-year Sharpe ratio of 25 Indian Large-Cap mutual funds through a multiple linear regression model. The model incorporated four predictor variables—Expense Ratio, Asset Under Management (AUM), Fund Age, and Turnover Ratio—to examine their combined and individual effects on risk-adjusted performance.

The regression analysis showed that the model has a moderate level of explanatory power, with an Adjusted R² of 0.17. The regression model is statistically significant at the 5 percentage level (ANOVA p = 0.02), confirming that the predictors as a group play a relevant role in explaining performance differences. However, the model’s overall strength is modest, as the selected variables collectively account for only 17 percent of the variation in the sample’s Sharpe ratios.

Among all variables, AUM emerged as the only statistically significant predictor, suggesting that larger funds tend to exhibit slightly higher risk-adjusted returns over the three-year period. This aligns with the preliminary scatterplot analysis, which indicated a weak-to-moderate positive relationship between AUM and Sharpe ratio.

The other predictors—Expense Ratio, Fund Age, and Turnover Ratio—did not show statistically significant effects in this model, although their inclusion helped ensure a comprehensive understanding of fund characteristics. The VIF scores confirmed no multicollinearity, validating the stability of the regression coefficients.





**Step 5**: **Interpreting Bivariate Scatterplot**
A Bivariate Scatterplot (created via Graphs > Scatterplot) was used for an initial assessment before developing the complete model. This plot specifically examined the relationship between two variables: 
the key predictor, Asset_under_management_in_crore, and the outcome, Three_year_Sharpe_ratio. The visual evidence suggested a positive but weak-to-moderate correlation, thereby confirming that AUM was an appropriate variable to include in the regression analysis.


<img width="590" height="337" alt="image" src="https://github.com/user-attachments/assets/86a29f4a-7fd1-43eb-8cfb-bc89c318577f" />






