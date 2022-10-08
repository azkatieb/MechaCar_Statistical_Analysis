# MechaCar_Statistical_Analysis

## Linear Refression to Predict MPG
When completing the multiple linear regression on the six variables included in the model: Vehicle Length, Vehicle Height, Spoiler Angle, Ground Clearance and AWD - it showed that the variables that provided a non-random amount of variance to the mpg values in the dataset were Vehicle Length and Ground Clearance as their p-value was lower than the .0001 variance. 

The slope of the linear model is not considered to be due to four of the six independent variables show correlation. 

This linear model does effectively predict the mpg of the MechaCar prototypes because The Multiple R-squared value is 0.7149 and the adjust R-squared is 0.6825. Becuase there are multiple variables that could affect the results of the linear model it would be suggested that the sample size be increased to help provide more reliable results. 
![linear model](/resources/Deliverable%201%20M15.png)

## Summary Statistics on Suspension Coils

Sample: 150 Observations

![Total Summary](/resources/Total%20Summary%20Deliverable%202.png)
Total Summary Table: mean, median, variance and standard deviation values for the PSI variable.

![Lot Summary](/resources/Lot%20Summary%20Deliverable%202.png)
Lot Summary Table: mean, median, variance and standard deviation values for the PSI variable by Manufacturing_Lot.

*Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?*
All lots in total as well as Lot 1 and Lot 2 individually do meet the design specifications. The Standard Deviation of the PSI and the variance PSI are very close to  the mean and median of the PSIs which shows they are meeting that specification. On the other hand for Lot 3, we can see that mean PSI is below the 1500 mark at 1496 and the variance is at 170.28 and the PSI is 13.05 standard deviations away. 

## T-Tests on Suspension Coils 

t.test across all manufacturing lots
Signifance Level: 0.05%
p-value: 0.06 (above significance level)
null hypothesis: not rejected

![all lots](/resources/All%20Lots%20Sample%20t-test.png)

t.test Lot 1
Signifance Level: 0.05%
p-value: 1 (above significance level)
null hypothesis: not rejected

![Lot 1](/resources/Lot%201%20Sample%20t-test.png)

t.test Lot 2
Signifance Level: 0.05%
p-value: 0.61 (above significance level)
null hypothesis: not rejected

![Lot 2](/resources/Lot%202%20Sample%20t-test.png)

t.test Lot 3
Signifance Level: 0.05%
p-value: 0.04 (below significance level)
null hypothesis: rejected

![Lot 3](/resources/Lot%203%20Sample%20t-test.png)

## Study Design: MechaCar vs Competition

The study we would design to compare MechaCar and the competetion would include the following metrics: car's cost, horsepower and engine cyliners, city fuel efficiency and highway fuel efficiency.

Our null hypothesis is that the MechaCar would be that there is not a statistically significant difference between the MechaCar and similarly priced and sized cars from the competition.

The statistical tests we would use to test our hypothesis would be the Two-sample t-Tests to compare the city fuel efficiency of both cars as well as the highway fuel efficiency of the MechaCar and the competition's cars. 

The data needed to run the study would be the following: 
- Vehicle Weight
- Vehicle Length
- Number of Engine Cylinders
- Number of Horsepower
- City Miles per Gallon 
- Highway Miles per Galloon