

### 1. Based on ROS 13.2 (3 points)
The following logistic regression model has been fit:

|   |  Median | MAD_SD  |
|---|---|---|
| (Intercept)   | -1.9  | 0.6  |
| x  | 0.7  | 0.8  |
| z  | 0.7  | 0.5  |

where x is a continuous parameter from 0 to 10 and z is a binary predictor taking on the values 0 and 1. Display the fitted model as two curves on a graph of P[y=1] vs. x.

(Optional:) How would you include uncertainty in the model fit?


### 2. Based on ROS 13.10 (5 points)
A randomized experiment is performed within a survey, and 1000 people are contacted. Half the people contacted are promised a $5 incentive to participate, and half are not promised an incentive. The result is a 50% response rate among the incentive group and a 40% response rate among the control group.

Write out a logistic regression model for this framework. Using the results above, construct a dataset and fit a logistic regression model for completing the survey as a function of the treatment (incentive). Finally interpret the results and plot your model fit.

### Based on ROS 14.4 (6 points)
Use the candy dataset to:

a. Analyze the relationship between predictors in the dataset and the outcome (whether the candy contains chocolate).

b. Fit several different versions of your model. Try including different predictors, interactions, and transformations of the predictors. Justify you selection of a model.

c. Based on the model you selected describe how each input affects Pr[chocolate = 1] and then use the model to make predictions for some test cases.
  
```
candy <- read_csv("https://math.montana.edu/ahoegh/teaching/stat446/candy-data.csv")
```
