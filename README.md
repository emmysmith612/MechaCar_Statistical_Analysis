# MechaCar_Statistical_Analysis 

## Overview of Project
For this assignment we were asked to assist in reviewing production data of the MechaCar. This prototype car is currently having various issues which is disrupting production progress. Due to this we will  

•	perform multiple linear regression analysis to identify the variables predicting the mpg of MechaCar.

•	collect summary statistics on PSI of suspension coils.

•	run t-tests to determine if the mean population is different from the manufacturing lots.

•	design a statistical study to compare the MechaCar performance vs other manufacturers' cars.
 

## Linear Regression to Predict MPG 

### 1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

*Both Vehicle length and ground clearance have p-values that are lower than 0.05. This means statistically they both have a significant relationship to the response variable (mpg) to the model.

### 2.Is the slope of the linear model considered to be zero? Why or why not?

*The slope is not considered to be zero because the p-value is lower than the value of 0.05.
   
### 3.Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

*The Multiple R-squared value is 0.7149, and the R adjusted value is 0.6825. The model predicts the MPG of MechaCar at a 71% rate. 

##  Summary Statistics on Suspension Coils
### 1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
*Total Summary 
![total_summary](https://user-images.githubusercontent.com/114880173/216228559-dbab697a-b561-4432-a096-eff0436b1387.PNG)
*Lot Summary
![lot_summary](https://user-images.githubusercontent.com/114880173/216228622-d32f0f57-bd46-421d-89bc-08b133d23d70.PNG)
*Based on the results, lot 1 and lot 2 meet the design specifications required within the limits of this metric. Lot 3, however, exceeds the maximum 100 pounds per square inch. 

## T-Tests on Suspension Coils 
![image](https://user-images.githubusercontent.com/114880173/216230013-8489be68-90db-4ab9-9c15-bb35fb150712.png)

![image](https://user-images.githubusercontent.com/114880173/216230146-f4dfca76-ebdc-4484-a5b8-51ea925b7f49.png)

![image](https://user-images.githubusercontent.com/114880173/216230228-6765d98c-f9c8-4aaf-a885-6d9697cef50e.png) 

![image](https://user-images.githubusercontent.com/114880173/216230280-6d942815-c3ca-4c27-8f04-cab0a8f34062.png)

## Study Design: MechaCar vs Competition 

### What metric or metrics are you going to test? 
*Fuel efficiency (miles per gallon) and price of the car. 

### What is the null hypothesis or alternative hypothesis?
*Null Hypothesis: MechaCar is cheaper and more fuel efficient than the competition. Alternative Hypothesis: MechaCar is more expensive and less fuel efficient.

### What statistical test would you use to test the hypothesis? And why?
*An ANOVA test can be used to determine the difference in means of fuel efficiency and cost between the two groups. 

### What data is needed to run the statistical test?
*A large sample size of competitors’ metrics on fuel efficiency and selling price for similar models to compare the mean to those of the MechaCar.



