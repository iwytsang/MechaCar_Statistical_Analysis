# MechaCar Statistical Analysis

## Linear Regression to Predict MPG
![image](https://user-images.githubusercontent.com/108503112/209883416-0b21b199-804d-4ff2-b7ae-2f8fdc794225.png)

Based on the Pr(>|t|) value, the variables that provided a non-random amount of variance to mpg values in the dataset would be VVehicle Weight, due to its value of 0.0776. A small Pr(>|t|) value means that the variables are unlikely to have a random relationship with the mpg value due to chance.

The slope is not zero due to the p-value being 5.35 x 10^11


The linear model does predict mpg of MechaCar prototypes effectively because of the Multiple R-squared value of 0.7149, meaning 71.49% of the variance found in the mpg is due to vehicle weight. 

## Summary Statistics on Suspension Coils
![image](https://user-images.githubusercontent.com/108503112/209722720-fede5a79-7c08-4c52-be3a-380c545e1fcd.png)


![image](https://user-images.githubusercontent.com/108503112/209722744-eaca25a1-a9a2-48a8-a30f-dfcc90ae802c.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Yes it meets the design specifications for all lots. However,, individually, it only fits for Lots 1 & 2. Not for Lot 3

## T-Tests on Suspension Coils
![image](https://user-images.githubusercontent.com/108503112/209742923-3353f46b-c5e9-4f14-a474-392281da9490.png)

briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
The t-test for all lots indicates that the true mean is equal to 1500.

![image](https://user-images.githubusercontent.com/108503112/209895632-bf4a8478-8699-43c7-9ca1-42b46b4f447d.png)
The t-test for lot 1 indicates that the true mean is equal to 1500.

![image](https://user-images.githubusercontent.com/108503112/209896169-2f09c629-5884-4fd6-bcbc-e3420f3c545b.png)
The t-test for lot 2 indicates that the true mean is equal to 1500.

![image](https://user-images.githubusercontent.com/108503112/209895993-3b14d73a-3fb2-4fb0-9c27-012a2e413096.png)
The t-test for lot 3 indicates that the true mean is not equal to 1500 and that the null (alternate) hypothesis is true.

## Study Design: MechaCar vs Competition
A statistical study between the MechaCar vs Competition would be that the mean cost of the MechaCar would be cheaper than a competitor's cost.
The null hypothesis would be that the mean cost of the MechaCar would not be cheaper than the competitor.
We would need to use the two-sample t-test to test the hypothesisn because we would have two samples - one from the MechaCar and one from another a competitor.
The data we would need would be the cost of all the MechaCar vehicles by vehicle ID, as well as the cost of the competitor's vehicles. 
