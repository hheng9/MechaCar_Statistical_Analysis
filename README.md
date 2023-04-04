# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
* ### The variables with significant impact on mpg are vehicle_length, ground_clearance, and the intercept.

* ### The slope of the linear model is not zero because at least one variable has a coefficient with a p-value less than 0.05.

* ### The model is effective in predicting mpg and shows 71.49% of the variance can be explained by the variables in the model. The AWD variable may not be statistically significant and further analysis may be needed to confirm if the assumptions of linear regression are met.

![D1-1](https://user-images.githubusercontent.com/118647523/229681764-d39a2d66-55b1-4e1e-b102-7aeb256a706e.png)

## Summary Statistics on Suspension Coils
### The total variance for all manufacturing lots combined is 62.29356 which is less than the specified maximum of 100 pounds per square inch. Lot1 has a variance of 0.9795918 which is below the limit. Lot2 has a variance of 7.4693878 and Lot3 has a variance of 170.2861224 both of which exceed the limit. Lots 2 and 3 do not meet the design specification for the variance of the suspension coils. This suggests that there may be issues with these two lots that need to be addressed. 

![D2-1](https://user-images.githubusercontent.com/118647523/229684560-ba3c354f-adbf-4908-a580-f3130234f52d.png)
![D2-2](https://user-images.githubusercontent.com/118647523/229684566-0837d74a-a87b-4dba-8c83-2c6a37493275.png)

## T-Tests on Suspension Coils

### The t-tests were conducted to determine whether the PSI for all manufacturing lots and each manufacturing lot individually is statistically different from the population mean of 1,500 PSI. The p-values were used to make this determination.

### For the PSI across all manufacturing lots, the p-value was 0.06028, which is greater than the significance level of 0.05. We fail to reject the null hypothesis and conclude that there is not sufficient evidence to suggest that the true population mean PSI is different from 1,500 PSI.

![D3-1](https://user-images.githubusercontent.com/118647523/229686810-1cf8053b-e019-4085-a41f-28d02173b117.png)

### Lot1 - the p-value was 1 indicating that we fail to reject the null hypothesis and conclude that the true population mean PSI is not statistically different from 1,500 PSI for Lot1.

![D3-2](https://user-images.githubusercontent.com/118647523/229686828-33548463-1eb4-4ffe-b27d-17a31b98e3cd.png)

### Lot2 - the p-value was 0.6072 which is greater than the significance level of 0.05. We fail to reject the null hypothesis and conclude that the true population mean PSI is not statistically different from 1,500 PSI for Lot2.

![D3-3](https://user-images.githubusercontent.com/118647523/229686862-4bf24422-ad24-4b3f-b443-bd4b5bbc2efe.png)

### Lot3 - the p-value was 0.04168 which is less than the significance level of 0.05. We reject the null hypothesis and conclude that the true population mean PSI is statistically different from 1,500 PSI for Lot3.

![D3-4](https://user-images.githubusercontent.com/118647523/229686889-1665884f-e20c-4636-8bfd-964493a119d5.png)

## Study Design: MechaCar vs Competition
### To compare the performance of MechaCar vehicles against the performance of vehicles from other manufacturers we could conduct a statistical study focusing on fuel efficiency and cost. We could compare the city and highway fuel efficiency and the cost of MechaCar vehicles to a sample of vehicles from other manufacturers in the same category.

### Null Hypothesis: There is no significant difference in the fuel efficiency and cost between MechaCar vehicles and vehicles from other manufacturers.

### Alternative Hypothesis: There is a significant difference in the fuel efficiency and cost between MechaCar vehicles and vehicles from other manufacturers.

### To test the hypothesis we could use a two-sample t-test with a significance level of 0.05. The t-test would be appropriate for comparing the means of two groups which would be the fuel efficiency and cost of MechaCar vehicles and other vehicles in the same category.

### To run the statistical test we would need data on the fuel efficiency for city & highway mileage and cost of MechaCar vehicles as well as a sample of vehicles from other manufacturers in the same category. We would also need sample of vehicles from other manufacturers and a larger population of vehicles in that category. We need to consider other factors that could affect fuel efficiency and cost such as the weight or horsepower of the vehicle to ensure accurate results.
