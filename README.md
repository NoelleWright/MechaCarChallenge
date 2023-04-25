# MechaCarChallenge

Overview of Project:

	The purpose of this analysis is to help Jeremy with  AutosRUs’ production totals in his new role. In his new position, management has called on to Jeremy to help with the team’s progress to help with the blocking of the manufacturing of the company. To complete this analysis, the R studio Program was used to determine Linear Regression and T-tests to help Jeremy with his data collection. 


Deliverable 1: 

In the first part of the analysis, R studio was used to help with mpg results for 50 prototype MechaCars. There were multiple variables used to help determine the linear regression of MPG. The variables included; vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance. In order to complete this, the mechacar.csv file was downloaded in the R studio. 
<img width="468" alt="image" src="https://user-images.githubusercontent.com/118686588/234427239-9587c118-f3a0-477a-8e98-4733e871ec15.png">

 

The picture shows the statistical analysis for the summary and r-squared values. 
1.	The variables that provided a non-random amount of variance were vehicle length and vehicle ground clearance. The reason is because they both have the smallest p-values that had no significant difference on the analysis. 
2.	The slope of the linear line is not zero because the p-value has an amount of 5.35e-11 which is way too small. It proves that the independent variables had effects on the dependent variables. 
3.	The linear model does predict MPG and is effective because the r-squared value, which is used to determine predictability, is 0.7149. This value indicates that 71% of all the mpg predictions were correct each time out of 100 times. 

Deliverable 2:

In deliverable 2, summary statistics were used on suspension coils. This process was used to determine if the weight on the suspension coils was consistent throughout all the lots from the manufacturer. A summary statistics table was used to determine PSI for all three lots with the mean, median, variance, and standard deviation. Below are images that depict the total summary as well as the Psi’s for each lot. 
 <img width="468" alt="image" src="https://user-images.githubusercontent.com/118686588/234427282-675754ce-68c5-4d4a-b49e-6db4c652cc8f.png">
<img width="468" alt="image" src="https://user-images.githubusercontent.com/118686588/234427299-39bed21b-6aaa-4029-9672-81d0df53be51.png">


Based off of the data, the current manufacturing design would need to be less than or equal to 100 PSI. With the diagram above, we can see that in the Var_PSI column, lots 1 and 2 are consistent with the manufacturing design in that their totals are less that 100 PSI. Lot 3 however, has a Var_PSI of 170 which exceeds the 100 PSI limit. This means that lot 3 is exceeding the design manufacturing. Jeremy could look at the designs from lots 1 and 2 to help have a direct correlation with lot 3


Deliverable 3:

T-Tests on Suspension Coils

<img width="408" alt="image" src="https://user-images.githubusercontent.com/118686588/234427373-e871d534-1869-48ee-a22c-6726e3b9601c.png">
<img width="402" alt="image" src="https://user-images.githubusercontent.com/118686588/234427396-c0ddc2f0-d14c-43ba-bb75-98f8f9ef9202.png">

 
 
With the results of the t-test, we can see the means of each lot. Lot 1 has a mean on 1500. Lot 2 has a mean of 1500.2 and lot 3 has a mean of 1496.14. The different means from the t-test state that the coils in lot 3 could have a possible problem causing them to have a lower mean score. The criteria of the coils should be 1500 and lot 3 has a significant decrease stating that there is a problem with the lots suspension coils. 

Deliverable 4:

Study Design MechaCar vs. Competition


With this study design, there would need to be different metrics to help with determining the performance differences between the MechaCar and performances from other companies. Some metrics that would be of interest could include; MPG, engine, maintenance, cost, and safety rating.   
1.	What metric or metrics are you going to test?
The metrics I would want to test are cost and safety rating.
2.	What is the null hypothesis or alternative hypothesis?
The null hypothesis is that cars in the same class have the same cost and safety rating. The alternative hypothesis is that all cars are not the same.
3.	What statistical test would you use to test the hypothesis? And why?
The statistical test I would use for the analysis would be linear regression for the cost as well as a t-test for the safety rating because there would be an independent and dependent variable with each test. 
4.	What data is needed to run the statistical test?
The data needed to run the statistical test would be the price point of maybe 50 cars as well as driving history with any problems with each car. 




![image](https://user-images.githubusercontent.com/118686588/234427153-4231ff29-f21d-4b47-b17e-8e2a6667eb15.png)
