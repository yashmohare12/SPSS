# Regression Analysis of Indian large Cap Mutual Funds

**Step 1**: **Data Structure and Variable Setup in SPSS**

The initial phase involved meticulously defining the dataset's structure within the SPSS "Variable View."

The setup was implemented as follows:
All variables designated for the analysis (including Fund_names, Three_year_Sharpe_ratio, and Expense_ratio) were uniformly defined as "Numeric" data types.
The "Fund_names" variable was categorized as "Nominal," and Value Labels were applied (e.g., 1.00 assigned to "ICICI PRUDENTIAL LARGE CAP FUNDS") to facilitate the identification of each distinct fund.
Every other variable intended for the subsequent regression analysis was set to the "Scale" measure.




**Step 2**: **Data Entry**
With the variables defined, the collected data for the 25 Large Cap funds was entered into the "Data View." Each row represents a single fund (a "case"), and each column represents one of the variables. Step 2: Data Entry and Structuring

Following variable definition, the collected empirical data for the 25 Large Cap mutual funds was systematically entered into the statistical software's "Data View."

This structured process is essential for rigorous statistical analysis. The "Data View" was configured as a matrix:
Rows as Cases: Each row represented a single fund (the observation unit).
Columns as Variables: Each column was reserved for a single metric (e.g., 3-Year Annualized Return).





**Step 3:** **Model Specification (Linear Regression)**

The core analysis utilized Multiple Linear Regression (accessible via Analyze > Regression > Linear...). The variables were defined as follows:
Dependent Variable: Three_year_Sharpe_ratio
Independent Variables (Predictors):
Expense_ratio
Asset_under_management_in_crore
Fund_age_in_years
Turnover_ratio_in_percentage






**Step 4**: **Output & Interpretation**
After running the analysis, the SPSS Output Viewer generated the key tables. These tables provided the complete statistical findings for the project:
Model Summary: Showed the Adjusted R-Square (0.17), indicating the model's explanatory power.
ANOVA: Showed the overall model's significance (p = 0.02).
Coefficients: Provided the p-values for each individual predictor (identifying AUM as significant) and the VIF scores (confirming no multicollinearity).







**Step 5**: **Interpreting Bivariate Scatterplot**
A Bivariate Scatterplot (created via Graphs > Scatterplot) was used for an initial assessment before developing the complete model. This plot specifically examined the relationship between two variables: 
the key predictor, Asset_under_management_in_crore, and the outcome, Three_year_Sharpe_ratio. The visual evidence suggested a positive but weak-to-moderate correlation, thereby confirming that AUM was an appropriate variable to include in the regression analysis.








