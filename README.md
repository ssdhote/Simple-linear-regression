# Simple-linear-regression

In ML Algorithms we have :

Supervised Learning
Unsupervised Learning
In Supervised Learning we have :

Regression
Classification
Firstly, we discuss about different types of Regressions

i. Linear Regression

a. Simple Linear Regression b. Multi-linear Regression

ii. Logistic Regression

iii. Lasso Regression

iv. Ridge Regression

In this repository we discuss about Simple Linear Regression

Simple Linear Regression:

  It is applicable when relationship between input variable and output variable is linear, that is it should have positive or negative correlation between input and output variable. That can be known using scatter plot.
  
  Here X is independent variable and Y is dependent variable, both X and Y are continuous.
  
  After getting scatter plot we will get a best fit line using *OLS (ordinary least squares) method*
  
            OLS method: we will find distance between actual and predicted value on the line and this is the error (e1), similarly for all data points e2,e3,.....
            
                           e1^2+e2^2+e3^2+...........+en^2=(error value)
                           
                                     which line will get this 'error value' as less that is best fit line.
                                     
             Now using this best fit line we will build a model.
             
             How can we say that model is best?
             
                1. R^2 - coefficient of determination
                
                   R^2 = explaines variation/total variation
                   
                   0<=R^2<=1
                   
                   if R^2 is nearly 1 => Good model
                   
                      R^2 is nearly 0 => Bad model
                      
                2. RMSE (Root Mean Square Error) should be less 
                
    To further improve the model we tried different transformations such as log transformation, Exponential Transformation, Quadratic Transformation
Data Used :-

Salary hike dataset :- Build a prediction model for the dataset
Delivery time dataset:- Predict delivery time using sorting time
Programming language: Python

The Codes regarding this Linear Regression model with two different business problems salary hike prediction ,delivery time prediction with their datasets are present in this Repository in details.
