# MechaCar_Statistical_Analysis
## Deliverable 1
### Linear Regression to Predict MPG
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  * Vehicle lenght
  * Ground Clearance
* Is the slope of the linear model considered to be zero? Why or why not?
  * No, it is not considered to be zero becuase none of the estimated for all coefficient are not equal to zero
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  * This model predicts the mpg of MechaCar protoypes because the Adjusted R-squared reflects that 68.25% of the variation within mpg is explained by the coefficients
![Deliverable_1](https://github.com/Smayorga97/MechaCar_Statistical_Analysis/blob/main/Resources/deliverable_1.png)
## Deliverable 2
### Summary Statistics on Suspension Coils
* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  * The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch, the overall summeary meets the design specifications. However when you look at the individual lots, you can see that Lot 1 and Lot 2 meet the requierements but Lot 3 does not.
![total_summary](https://github.com/Smayorga97/MechaCar_Statistical_Analysis/blob/main/Resources/total_summary.png)
![lot_summary](https://github.com/Smayorga97/MechaCar_Statistical_Analysis/blob/main/Resources/lot_summary.png)
## Deliverable 3
### T-Tests on Suspension Coils
![t_test_!.png](https://github.com/Smayorga97/MechaCar_Statistical_Analysis/blob/main/Resources/t_test_!.png)

T-test for lot 1: there is no statistical difference

![t_test_2.png](https://github.com/Smayorga97/MechaCar_Statistical_Analysis/blob/main/Resources/t_test_2.png)

T-test for lot 2: there is no statistical difference

![t_test_3.png](https://github.com/Smayorga97/MechaCar_Statistical_Analysis/blob/main/Resources/t_test_3.png)

T-test for lot 3: there is a statistical difference

## Deliverable 4
* What metric or metrics are you going to test?
I would tests the resale value, average annual cost of ownership and MPG
* What is the null hypothesis or alternative hypothesis?
Null Hypothesis: the resale price value of MechaCar is affected by the cost of ownership and MPG throughout the years
* What statistical test would you use to test the hypothesis? And why?
A multiple linear regression would show the corrolations between all the veriables.
* What data is needed to run the statistical test?
  * MPG
  * Average annual cost of ownership throughout the years
  * resale value after 10 years from a big population with same characteristics.
