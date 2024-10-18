# Processing_Data_MaxPlanck
Clean outliers and Fit sine functions
1. Clean outliers by the moving median algorithm at a sliding window = days(30), statistical threshold = 2.5; then fill out missing values by Piecewise Cubic Hermite Interpolating Polynomial (PCHIP).
2. Fit time series by the combination of sine functions with a fitting option object: Non-linear Least Squares
