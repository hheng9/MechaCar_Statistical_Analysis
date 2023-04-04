# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Based on the coefficients' p-values, the variables that provided a non-random amount of variance to the mpg values in the dataset are: intercept, vehicle_length, and ground_clearance. Their p-values are all less than 0.001, indicating that it is very unlikely that the coefficients for these variables are equal to zero.

No, the slope of the linear model is not considered to be zero, because at least one variable (vehicle_length) has a coefficient with a p-value less than 0.05 (in fact, all variables except AWD have a p-value less than 0.05). This means that there is evidence to suggest that the variables are related to the response variable (mpg).

The linear model seems to predict the mpg of MechaCar prototypes effectively, as indicated by the high R-squared value of 0.7149. This means that 71.49% of the variance in the response variable (mpg) can be explained by the variables in the model. However, it is important to note that the p-value for the AWD variable is relatively high (0.1852), indicating that it may not be statistically significant in predicting the mpg. Additionally, further analysis would be required to determine if the assumptions of linear regression (e.g., normality of residuals, linearity, homoscedasticity) are met by this model.


### The variables with significant impact on mpg are vehicle_length, ground_clearance, and the intercept.

### No, the slope of the linear model is not zero because at least one variable has a coefficient with a p-value less than 0.05.

### The model is relatively effective in predicting mpg (71.49% of the variance can be explained by the variables in the model), but the AWD variable may not be statistically significant, and further analysis is needed to confirm if the assumptions of linear regression are met.
