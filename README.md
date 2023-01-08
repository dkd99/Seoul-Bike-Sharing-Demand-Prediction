# Seoul-Bike-Sharing-Demand-Prediction
# Problem Description 

 Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

# Project Summary-

A bicycle-sharing system, bike share program, public bicycle scheme or public bike share (PBS) scheme is a shared transport service in which bicycles are made available for shared use to individuals on a short-term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" and return it at another dock belonging to the same system.

It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time.


*   There are many variables related to weather conditions like temperature,rainfall,snowafall,Windspeed which affect demand of bikes.How did these variables affect the demand in available was analysed using various graphs. 

*   How does demand changes during different hours of day was also analysed.Does closing and opening of offices,colleges affect demand.Which hour have peak demand.

*   Whether Holidays lower demand as compared to working day was also analysed.

The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

We have around 8760 hours of observations for the whole year that cover all seasons and weather conditions to predict the demand of rental bikes at any particular hour using supervised machine learning algorithms.

This is a regression problem that comes under supervised machine learning.Linear and Non linear models were used for this problem.

Approach- 

This problem has been solved following these steps-

*   Data understanding
*   Data exploration
*   Feature engineering
*   Model training
*   Model validation 
*   Error analysis-Mean square error,mean absolute error,r2 score for test and train score,adjusted r2 score were calculated and compared for various models.
# Conclusion
1)We observed that bike rental count is high during no holidays  than holidays. 

2)The rental bike counts was at its peak at 8 AM in the morning and 6pm in the evening,  an increasing trend can be observed from 5am to 8am, the graph touches the peak at 8am in the morning then dips a bit. Later we can see a gradual increase in the demand until 6pm, the demand is highest at 6 pm, and reduces until midnight.

3)People prefered to rent bikes when temperature was between 20 degrees to 35 degrees celsius temperature and even when it is little windy.

4)Highest bike rental count was found  in Autumn and summer seasons and the lowest is in winter season. 

5)Bike rentals were highest during the clear days and lowest on snowy and rainy days.

6)When there was not a functioning day no bikes were booked. 

7)Linear models such as linear regression ,lasso,ridge are performing good on both train and test data.R2 score is around 0.8 for both train and test set.

8)Polynomial regression is giving better results than linear models and giving a good r2 score on both test and train set.r2 score is around 0.85 for both train and test sets.

9)Ensemble models are giving quite good results on train data i.e R2 score more than 0.9 but are a little bit overfit i.e 	r2 score of 0.86-0.88 on test data.
