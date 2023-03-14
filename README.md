# LinearRegressionAssignmentBoomBikes
->Linear Regression Assignment on Boombikes Casestudy
->I have build a Multiple Linear Regression Model for demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer expectations.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

So, I have built a multiple Linear Regression model keeping in consideration multicollinearity of the variables in the dataset to built a model which will help in answering which are significant variables for predicting the demand of the Boombikes and how well these variables will describe the demand for shared bikes:-
The steps to be followed in this exercise are as follows:
1.Reading, understanding and visualizing the data
2.Preparing the data for model training (train-test split, rescaling)
3.Training the model
4.Residual analysis
5.Prediction and evaluation of the test set

## Conclusions
Summary - Following points were summarized after performing the Multiple Linear Regression Model building for the Boombikes Casestudy
using data interpretation, visualisation, data-preparation, model building and training, residual analysis 
and evaluation of test model:-
1.The R-squared value of the train set is 82.8% whereas the test set has a value of 79.98% which suggests that our model 
broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
2.Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that 
the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables.
RFE was also conducted for automated selection of variables.
3.We can see that temperature variable is having the highest coefficient 0.5398, which means if the temperature increases 
by one unit the number of bike rentals increases by 0.5398 units. So, Boombikes can focus more on temperature factor.
Additionally more rentals seem to be demanded on the winters as compared to the summer and spring.
We had observed that the months of September and October had higher use of rentals. In terms of days the maximum 
focus was on days like Wed, Thurs and Sat and more on holidays.
4.Boombikes rentals were more in 2019 as compared to 2018, So people are getting more used to shared bikes concept and hence, 
usage of the shared bikes concepts will flourish more in cmoing years with people opting for this method more and more.
5.Negative coefficients or negative correlation with the count were seen on Holidays and Sundays, as people more want to 
stay at home on those days. Hence strategic and marketing offers can be provided on these days. Also, during Light snow 
and Mist + Cloudy weather, the bike rentals are in negative correlation, so on those days, disconts can be given.



## Acknowledgements
https://en.wikipedia.org/wiki for Subjective questions.


## Contact
Created by [@Sa2019Si] - feel free to contact me!


