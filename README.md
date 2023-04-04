# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![D1-1](https://user-images.githubusercontent.com/118647523/229681764-d39a2d66-55b1-4e1e-b102-7aeb256a706e.png)

Based on the coefficients' p-values, the variables that provided a non-random amount of variance to the mpg values in the dataset are: intercept, vehicle_length, and ground_clearance. Their p-values are all less than 0.001, indicating that it is very unlikely that the coefficients for these variables are equal to zero.

No, the slope of the linear model is not considered to be zero, because at least one variable (vehicle_length) has a coefficient with a p-value less than 0.05 (in fact, all variables except AWD have a p-value less than 0.05). This means that there is evidence to suggest that the variables are related to the response variable (mpg).

The linear model seems to predict the mpg of MechaCar prototypes effectively, as indicated by the high R-squared value of 0.7149. This means that 71.49% of the variance in the response variable (mpg) can be explained by the variables in the model. However, it is important to note that the p-value for the AWD variable is relatively high (0.1852), indicating that it may not be statistically significant in predicting the mpg. Additionally, further analysis would be required to determine if the assumptions of linear regression (e.g., normality of residuals, linearity, homoscedasticity) are met by this model.


### The variables with significant impact on mpg are vehicle_length, ground_clearance, and the intercept.

### No, the slope of the linear model is not zero because at least one variable has a coefficient with a p-value less than 0.05.

### The model is relatively effective in predicting mpg (71.49% of the variance can be explained by the variables in the model), but the AWD variable may not be statistically significant, and further analysis is needed to confirm if the assumptions of linear regression are met.

## Summary Statistics on Suspension Coils
The total variance for all manufacturing lots combined is 62.29356, which is less than the specified maximum of 100 pounds per square inch. However, when looking at each lot individually, Lot1 has a variance of 0.9795918, which is below the limit, while Lot2 has a variance of 7.4693878 and Lot3 has a variance of 170.2861224, both of which exceed the limit. Therefore, Lots 2 and 3 do not meet the design specification for the variance of the suspension coils. This suggests that there may be issues with the manufacturing process in these two lots that need to be addressed. 

![D2-1](https://user-images.githubusercontent.com/118647523/229682934-83c934da-c76b-43c5-ac05-69ae4227580e.png)
![D2-2](https://user-images.githubusercontent.com/118647523/229682941-d556b421-ea61-4984-bfb6-0460dca070fb.png)

