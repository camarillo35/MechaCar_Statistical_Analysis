# MechaCar_Statistical_Analysis

Deliverable 1 Summary
The MechaCar_mpg.csv dataset contains mpg test results for 50 prototype MechaCars. The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Using R we will design a linear model that predicts the mpg of MechaCar prototypes using several variables/Coefficients.

Using the script to calculate the linear regression and the summary of linear regression model we can determine the p-value and the r-squared value.

<img width="650" alt="1 A" src="https://user-images.githubusercontent.com/92793248/153610796-027fb992-1bac-483d-9c94-3cdd28847cbe.png">

Predictions for linear regression

There are no variables that provide a non-random amount of variance to the mpg values in the dataset because the pr(>|t|) value is greater than 0.05. Which means that it has no significant impact on the mpg values and we can reject the null hypothesis.
The slope of the linear model is not considered to be zero because all the variables/coefficients are directly proportional to the mpg vales.
The linear model does not predict mpg of MechaCar prototypes effectively because the p value of the multiple linear regression is 5.35e-11 which is higher than 0.05 and is not signficant.


Deliverable 2 Summary 
The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots.
We will calculate the following using R

The total_summary in the below table shows the mean, median, variance and SD for the PSI for suspension coil across all manugacturing units, and the variance of the suspension coil is under 100 PSI.

The lot_summary in the below table shows the mean,median, variance and SD for the PSI for suspension coil across all manufacturing units individually. Looking at the table we can see the variance of Lot3 is higher than 100 PSI which is not acceptable.

<img width="356" alt="2 A" src="https://user-images.githubusercontent.com/92793248/153610867-0e9fc2b2-6d62-4e37-b68d-c50da5272d57.png">


<img width="503" alt="2 B" src="https://user-images.githubusercontent.com/92793248/153610903-6f38deea-d562-42c1-8a3f-8a1d8a016ed7.png">

The design specifications for the MechaCar suspension coils dictates that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data meets this design specification for all manufacturing lots in total which is below 100 PSI.But when we look at the lots individually we can see that Lot3 has PSI higher than 100.



<img width="550" alt="3 A" src="https://user-images.githubusercontent.com/92793248/153610999-518351fc-4ec1-40d2-a66c-0444cb8c4f2d.png">




<img width="550" alt="3 B" src="https://user-images.githubusercontent.com/92793248/153611024-3bedf413-ae8f-4be2-aa37-489cfe09c626.png">




<img width="550" alt="3C" src="https://user-images.githubusercontent.com/92793248/153611069-b16eb6c2-4d83-47e0-8318-929ad9cd72b6.png">




<img width="550" alt="3 D" src="https://user-images.githubusercontent.com/92793248/153611117-0e14e7ec-fd11-40ef-b42d-2c4191654b93.png">



