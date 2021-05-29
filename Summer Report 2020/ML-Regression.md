                                                                       🎓  SUMMER TRAINING REPORT
                                                                                    On
                                                                        MACHINE LEARNING - REGRESSION


                                                 Submitted to Guru Gobind Singh Indraprastha University, Delhi (India)
                                             in partial fulfillment of the requirement for the award of the degree of B.TECH

                                                                                    in

                                                                  ELECTRONICS AND COMMUNICATIONS ENGINEERING

                                                                                Submitted By
                                                                              MAYANK CHOUDHARY

                                                                            Roll. No. 35515002818


 

                                                                  DEPTT. OF ELECTRONICS AND COMMUNICATIONS

                                                               🏫MAHARAJA SURAJMAL INSTITUTE OF TECHNOLOGY ,
                                                                             NEW DELHI-110058

                                                                                AUGUST 2020






👩‍🏫👨‍🏫
# ACKNOWLEDGEMENT

A research work owes its success from commencement to completion, to the people in love with researchers at various stages. Let me in this page express my gratitude to all those who helped us in various stage of this study. First, I would like to express my sincere gratitude indebtedness to Mr. PUNEET AZAD (HOD, Department of Information Technology, Maharaja Surajmal Institute of Technology,New delhi) for allowing me to undergo the summer training of 30 days at ………...................................COURSERA................................................


I am grateful to my instructors  Carlos Guestrin & Emily Fox for this easy to learn course and their way of teaching marks a really strong effect.
      

Last but not least, I pay my sincere thanks and gratitude to all the Staff Members of
Maharaja Surajmal Institute of Technology,New delhi for their support and for making our training valuable and fruitful.




📝
# Contents


1. Simple Linear Regression                
1.1  Build a generic simple linear regression function
1.2  Residual Sum of Squares

2. Multiple Regression
2.1   Running a multiple regression

3. Assessing Performance

4. Ridge Regression
4.1   Polynomial regression, revisited
4.2   Selecting an L2 penalty via cross-validation

5. Feature Selection & Lasso
5.1   Learn regression weights with L1 penalty
5.2   Selecting an L1 penalty
5.3   Exploring the larger range of values to find a narrow range with the desired sparsity

6. Nearest Neighbors & Kernel Regression
6.1   Split data into training, test, and validation sets
6.2   Perform 1-nearest neighbor regression
6.4   Make multiple predictions
6.5   Choosing the best value of k using a validation set

References	
							
•	Coursera online training course 
•	Google Images










## Week 1: Simple Linear Regression


Our course starts from the most basic regression model: Just fitting a line to data. This simple model for forming predictions from a single, univariate feature of the data is appropriately called "simple linear regression". In this module, we describe the high-level regression task and then specialize these concepts to the simple linear regression case. We learn how to formulate a simple regression model and fit the model to data using both a closed-form solution as well as an iterative optimization algorithm called gradient descent. Based on this fitted function, we will interpret the estimated model parameters and form predictions. We will also analyze the sensitivity of our fit to outlying observations. We will then examine all of these concepts in the context of a case study of predicting house prices from the square feet of the house.


## Regression Week 2: Multiple Regression (Interpretation)

The goal of this first notebook is to explore multiple regression and feature engineering with existing Turi Create functions.
In this notebook you will use data on house sales in King County to predict prices using multiple regression. You will:
	Use SFrames to do some feature engineering
	Use built-in Turi Create functions to compute the regression weights (coefficients/parameters)
	Given the regression weights, predictors and outcome write a function to compute the Residual Sum of Squares
	Look at coefficients and interpret their meanings
	Evaluate multiple models via RSS


## Regression Week 3: Assessing Fit (polynomial regression)

In this notebook you will compare different regression models in order to assess which model fits best. We will be using polynomial regression as a means to examine this topic. In particular you will:
	Write a function to take an SArray and a degree and return an SFrame where each column is the SArray to a polynomial value up to the total degree e.g. degree = 3 then column 1 is the SArray column 2 is the SArray squared and column 3 is the SArray cubed
	Use matplotlib to visualize polynomial regressions
	Use matplotlib to visualize the same polynomial degree on different subsets of the data
	Use a validation set to select a polynomial degree
	Assess the final fit using test data
We will continue to use the House data from previous notebooks.



## Regression Week 4: Ridge Regression (interpretation)

In this notebook, we will run ridge regression multiple times with different L2 penalties to see which one produces the best fit. We will revisit the example of polynomial regression as a means to see the effect of L2 regularization. In particular, we will:
Use a pre-built implementation of regression (Turi Create) to run polynomial regression
Use matplotlib to visualize polynomial regressions
Use a pre-built implementation of regression (Turi Create) to run polynomial regression, this time with L2 penalty¶
Use matplotlib to visualize polynomial regressions under L2 regularization
Choose best L2 penalty using cross-validation.
Assess the final fit using test data.
We will continue to use the House data from previous notebooks. (In the next programming assignment for this module, you will implement your own ridge regression learning algorithm using gradient descent.)



## Regression Week 5: Feature Selection and LASSO(Interpretation)

In this notebook, you will use LASSO to select features, building on a pre-implemented solver for LASSO (using Turi Create, though you can use other solvers). You will:
	Run LASSO with different L1 penalties.
	Choose best L1 penalty using a validation set.
	Choose best L1 penalty using a validation set, with additional constraint on the size of subset.
In the second notebook, you will implement your own LASSO solver, using coordinate descent.


     
## Regression Week 6: Predicting house prices using k-nearest neighbors regression¶

In this notebook, you will implement k-nearest neighbors regression. You will:
	Find the k-nearest neighbors of a given query input
	Predict the output for the query input using the k-nearest neighbors
	Choose the best value of k using a validation set


References


The complete training report is based on the online training course from Coursera Machine Learning Course……………..https://www.coursera.org 


                                                                             …………END………….

