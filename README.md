# MechaCar__Statistical_Analysis


The purpose of this analysis is to offer insights on the MechaCar's production to help the manufacturing team. In order to conduct this analysis, I am using two datsets containing information related to the miles per gallon and the suspension coils of the MechaCar. I am using the programming language R and its dplyr library to complete this analysis.

According the summary results, vehicle length, ground clearence, and interecept are statistically unlikely to provide randomn results of variance to the linear model. In other words, vehicle length and ground clearence have a significant impact on mpg.
The p-value is much smaller then the significance level of 0.05. There is sufficient evidence that the slope of the linear model is not 0.
With an R-squared of 0.71 there is a moderate to strong chance that this linear model is effective at predicting mpg. There is a 71% chance that the variability of mpg is explained using this linear model.

The current manufacturing data meets the design specification of not exceeding 100 psi for Lot 1 and Lot 2.
Lot3 does not meet the design specification with a variance of 170 psi which exceeds the 100 threshold for this excercise.
The reason for the high variance in Lot3 is due to outliers 


The transport sector is one of the largest sources of CO2 emissions and a major source of air pollution.

Is the MechCar prototype better for our enviornment than it's competitors?

To test for MechaCar and it's competitors impact on the enviorment, we will perform a statistical analysis based on the following metrics:

 - CO2 Emissions
 - MPG
Null Hypothesis: There is no difference in CO2 emissions between MechaCar and its competitors.

Alternate Hypothesis: There is a difference in CO2 emissions between MechCar and its competitors.

Statisitcal Test: T-Tests on CO2 Emissions

Data needed: CO2 emissions for MechCar and their competitors in a dataframe
