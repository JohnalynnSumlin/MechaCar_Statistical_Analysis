# MechaCar_Statistical_Analysis


A few weeks after starting his new role, Jeremy is approached by upper management about a special project. AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. AutosRUs’ upper management has called on Jeremy and the data analytics team to review the production data for insights that may help the manufacturing team.

In this challenge, you’ll help Jeremy and the data analytics team do the following:

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

### What You're Creating
This new assignment consists of three technical analysis deliverables and a proposal for further statistical study. You’ll submit the following:

* Deliverable 1: Linear Regression to Predict MPG
* Deliverable 2: Summary Statistics on Suspension Coils
* Deliverable 3: T-Test on Suspension Coils
* Deliverable 4: Design a Study Comparing the MechaCar to the Competition

## Linear Regression to Predict MPG

With the multiple linear regression model, we are assessing if there is a realtionship between variagbles and the mpg of MechaCar prototypes.

For multiple linear regression model, following hypothesis will help to understand significant linear relationship between values:

H0: The slope of the linear model is zero, or m = 0 (If there is no significant linear relationship, each dependent value would be determined by random chance and error. Therefore, our linear model would be a flat line with a slope of 0).

Ha: The slope of the linear model is not zero, or m ≠ 0 (If there is significant linear relationship, each dependent value would not be determined by random chance and error. Therefore, our linear model would not be a flat line with a slope greater or lesser than 0).


## Summary Statistics on Suspension Coils

* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

* Currently, the manufacturing data does meet this design specification for all manufacturing lots in total, with a Variance of 62. 

* The data does not meet the design criteria per individual lots because lot 3 is at a variance of 170. This is 70% over the limit.


## T-Tests on Suspension Coils

We are performing a one-sample t-test. This is used to determine whether there is a statistical difference between the means of a sample dataset and a population dataset with a given mean of 1,500 PSI. Here is the hypothesis we are establishing:

H0: There is no statistical difference between the suspension coil data set mean and its presumed population mean of 1,500 PSI.

Ha: There is statistical difference between the suspension coil data set mean and its presumed population mean of 1,500 PSI.

In order to reject or fail to reject our null hypothesis we have to look at the p-value that determines if there is a statistical difference between the observed sample mean and its presumed population mean. According to the result p-value for all manufacturing lots is 0.06028, for lot 1 = 1, for lot 2 = 0.6072, and for lot 3 = 0.04168. In both lot 1 and lot 2 cases p-value is above the assumed significance level of 0.05. Therefore, there is not enough evidence, and we fail to reject the null hypothesis, meaning that the two means not statistically different.

## Study Design: MechaCar vs Competition

