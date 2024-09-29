# This data project has been used as a take-home assignment in the recruitment process for the data science positions at Apollo Hospitals.
# Apollo Hospitals: Hypothesis Testing

## Goal
Analyze patient-level data to answer the following questions for Apollo Hospitals:

### Predicting the Reason for Hospitalization
1. Identify significant variables that predict hospitalization across different regions.
2. Determine how variables like viral load, smoking, and severity level influence hospitalization charges.

## Steps to Approach

### Data Understanding
1. Load the dataset.
2. Examine the columns, datatypes, and missing values.
3. Understand the statistical properties of the dataset using summary statistics.

### Data Cleaning & Preparation
1. Handle missing data (if any).
2. Convert categorical variables (sex, smoker, region) into numeric format for analysis.
3. Ensure all data types are appropriate for modeling and visualization.

### Exploratory Data Analysis (EDA)
1. **Univariate Analysis**: Explore the distribution of individual variables (age, sex, smoker status, region, viral load, severity level, and hospitalization charges).
2. **Bivariate Analysis**: Investigate relationships between key variables like age vs. charges, severity level vs. viral load, etc.
3. **Multivariate Analysis**: Use correlation matrices and heatmaps to understand how variables interact with one another.

### Predicting Hospitalization Reasons (by Region)
1. Investigate which variables differ significantly across regions.
2. Use statistical tests like ANOVA or Chi-Square to identify region-specific predictors.
3. **Model Approach**:
    - Encode region into a categorical variable.
    - Use logistic regression or multinomial logistic regression to predict hospitalization reasons.

### Predicting Hospitalization Charges
1. Build a regression model to estimate hospitalization charges using the independent variables (age, sex, smoker, region, viral load, severity level).
2. Use linear regression or ridge/lasso regression to estimate the relationship between hospitalization charges and predictors.
3. Investigate the relative importance of viral load, smoker, and severity level in explaining the charges.
4. Test model performance with appropriate metrics (R-squared).

### Statistical Tests
1. Use ANOVA to test if hospitalization charges vary significantly by region.

2. Use correlation tests to evaluate relationships between continuous variables (e.g., viral load, severity, charges).

### Visualizations
1. **Histogram Plots**: Compare hospitalization charges across regions, smoking status, and severity levels.
2. **Scatter Plots**: Examine relationships between viral load, severity, and charges.
3. **Heatmaps**: Show correlations between continuous variables.
4. **Bar Plots**: For categorical data like region-wise distribution of patients or smoker status.
5. **Box Plots**: Compare hospitalization charges across regions, smoking status, and severity levels.
