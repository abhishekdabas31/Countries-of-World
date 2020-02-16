# Exploratory Data Analysis of Countries in World:-
I have used EDA to find factors affecting a country's GDP per capita in order to make a predictive model of model countries GDP using linear regression. The hope is to find independent variables with a strong linear relation to the depenedent variable GDP ($ per capita).

# Modelling of data
There are two types of supervised machine learning algorithms:  `Regression and classification`
The former predicts continuous value outputs while the latter predicts discrete outputs. For instance, predicting the price of a house in dollars is a regression problem whereas predicting whether a tumor is malignant or benign is a classification problem.
> Linear Regression Theory
The term “linearity” in algebra refers to a linear relationship between two or more variables. If we draw this relationship in a two-dimensional space (between two variables), we get a straight line.
Linear regression performs the task to predict a dependent variable value (y) based on a given independent variable (x). So, this regression technique finds out a linear relationship between x (input) and y(output). Hence, the name is Linear Regression. If we plot the independent variable (x) on the x-axis and dependent variable (y) on the y-axis, linear regression gives us a straight line that best fits the data points
The equation of the above line is :
`Y= mx + b`
>> There can be multiple straight lines depending upon the values of intercept and slope. Basically what the linear regression algorithm does is it fits multiple lines on the data points and returns the line that results in the least error.

This same concept can be extended to cases where there are more than two variables. This is called `multiple linear regression`. For instance, consider a scenario where you have to predict the price of the house based upon its area, number of bedrooms, the average income of the people in the area, the age of the house, and so on. In this case, the dependent variable(target variable) is dependent upon several independent variables. A regression model involving multiple variables can be represented as:
`y = b0 + m1b1 + m2b2 + m3b3 + … … mnbn`
This is the equation of a hyperplane.
Remember, a linear regression model in two dimensions is a straight line;
in three dimensions it is a plane, 
and in more than three dimensions, a hyperplane.



# "Countries of World.csv" :-
## The Data
GDP ($ per capita) (Target - the dependent variable)

Possible independent variables (predictors)

Country
Region
Population
Area (sq. mi.)
Pop. Density (per sq. mi.)
Coastline (coast/area ratio)
Net migration
Infant mortality (per 1000 births)
Literacy (%)
Phones (per 1000)
Arable (%)
Crops (%)
Other (%)
Climate
Birthrate
Deathrate
Agriculture
Industry
Service