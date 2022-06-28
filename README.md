# MechaCar Statistical Analysis Using R

## Purpose of Review

AutosRUs asked my team to review the new MechaCar as it has been suffering with production troubles. I have been asked to produce a analysis on the current data to see if I can assist the production team on where the issues are happening. 

In this review I have done several statitical analysis techniques:
  1) Linear regressions on mpg
  2) PSI review using summary statistics
  3) T-tests to see if the manufacturing lots differ from the mean
  
## Linear Regression to Predict MPG

### Linear Regression Results

![Linear Regression of MechaCar Data](https://user-images.githubusercontent.com/100856534/176267847-195ec5d0-3075-48b7-855f-1ae164379b2b.png)

### Summary of Linear Regression Results

![Summary of Linear Regression](https://user-images.githubusercontent.com/100856534/176267905-8c1abcb9-e4a4-46f8-98ca-c3e28c694b08.png)

### Analysis Review

**Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

Upon rewiew of the variables it looks like both vehucle lenght and ground-clearence are likely to have non-random amounts of variance to the MechCar, whic effects the MPG.

**Is the slope of the linear model considered to be zero? Why or why not?**

Looking at the slope of the regression, the p-value is 5.35e-11. Meaning that the slope is not 0. 

**Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

The adjusted R-squared value is .6825, which makes this statistically more so than not able to predict the MPG of the MechaCar.

## Summary Statistics on Suspension Coils

### Total Summary

![total_smmary](https://user-images.githubusercontent.com/100856534/176270300-6256645f-9c40-4a90-abca-69434ba88485.png)

### Lot Summary

![lot_summary](https://user-images.githubusercontent.com/100856534/176270351-f9c112c9-41d5-4e98-bd7c-c7f50c886a6e.png)

### Analysis Review

**The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**

Upon review of the Total Summary informaiton the variance is well below the need 100 PSI as dicatated by manufacturing standards. However, when the lots are sorted by their own Lot 3 is 70 PSI off. 

## T-Tests on Suspension Coils

### All Lots T-Tests

![all lots suspension coils psi](https://user-images.githubusercontent.com/100856534/176272527-5b412aeb-8ee0-48f5-ae01-cf8d8bda534e.png)

### Lot 1

![Lot 1 Test](https://user-images.githubusercontent.com/100856534/176272547-98f14088-398f-4297-b12c-94b799e87ff6.png)

### Lot 2

![Lot 2 Test](https://user-images.githubusercontent.com/100856534/176272566-d190bd19-cc52-41fd-bc30-22abaa297265.png)

### Lot 3

![Lot 3 Test](https://user-images.githubusercontent.com/100856534/176272585-ec9071b1-bf72-4c93-af4a-b410dbd11bbd.png)

### Summary of T-Tests

When reviewing the All Lots analysis you can see that the p-value is 0.06, this is higher than the common significance of 0.05. The mean of all three lots are stitisically similar, when compared to the estimated population mean of 1500.

Lot 1 - has a mean of 1500 and a p-value of 1. This lot is matching what is expected from the population. 

Lot 2 - has a mean of 1500 and a p-value of .60. This lot is statistically similiar to Lot 1

Lot 3- has a mean of 1496 and a p-value of .42. This lot, which has been shown in other statistical reviews, is statistically different than the other two lots. 

## Study Design: MechaCar vs Competition








