# MechaCar_Statistical_Analysis

## Deliverable 1
## Linear Regression to Predict MPG

![Del 1](https://user-images.githubusercontent.com/66224990/189493402-1ebd675b-f807-4643-9e57-c530c2de53b5.png)

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Answer: vehicle_length and ground_clearance
- Is the slope of the linear model considered to be zero? Why or why not?
- Answer: Yes the values are to the negative 8th and 12th, which is reasonably close to zero.
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- Answer: The Multiple R - Squared value is 0.7149, which is fairly good but could be better.

## Deliverable 2

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. - Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- Answer: Yes and no. When the lots were analyzed together it was below 100. When analyzed individually Lots 1 and 2 had very low variance, close to zero however Lot 3 was above 100. 

## Deliverable 3

## T-Tests on Suspension Coils

Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

![Del 3 T Test](https://user-images.githubusercontent.com/66224990/189492576-50470a37-d65f-4b3f-b413-df154662d632.png)

All Lots
statistically different p-value = 0.06028

Lot 1
statistically similar p-value = 1

Lot 2
statistically similar p-value = 0.6072

Lot 3
statistically different p-value = 0.04168


## Deliverable 4

## Study Design: MechaCar vs Competition

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:
- What metric or metrics are you going to test?
- Answer: I would test horse power and fuel efficiency
- What is the null hypothesis or alternative hypothesis?
- Answer: Null hypothesis is on average cars with higher horsepower get less miles to the gallon. Alternative hypothesis is on average cars with higher horsepower get more miles to the gallon.
- What statistical test would you use to test the hypothesis? And why?
- Answer: I would do a Multiple Linear Regression test because we are testing 2 variables. 
- What data is needed to run the statistical test?
- Answer: We need the horsepower and miles to the gallon for various vehicles. 
