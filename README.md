# Predict-Prices-of-Airline-Tickets
This study shows that it is feasible to predict the airline ticket price based on historical data. One possible way to increase the accuracy can be combining different models after carefully studying their own performance on each individual bin.

## About the project

Optimal timing for airline ticket purchasing from the consumer’s perspective is challenging principally because buyers have insufficient information for reasoning about future price movements. In this project we simulate various models for computing expected future prices and classifying whether this is the best time to buy the ticket.

## Why this Project ?

Anyone who has booked a flight ticket knows how unexpectedly the prices vary. Airlines use using sophisticated quasi-academic tactics which they call "revenue management" or "yield management". The cheapest available ticket on a given flight gets more and less expensive over time.

This usually happens as an attempt to maximize revenue based on :

- Time of purchase patterns (making sure last-minute purchases are expensive)
- Keeping the flight as full as they want it (raising prices on a flight which is filling up in order to reduce sales and hold back inventory for those expensive last-minute expensive purchases)


## Model Building
###### LinearRegression
![17](https://user-images.githubusercontent.com/108620000/190868351-52dd90f2-50d6-4779-8736-da3f171a7ed2.PNG)

###### KNeighborsRegressor
![18](https://user-images.githubusercontent.com/108620000/190868360-bdb2b37e-a460-4833-b115-8b195388e65a.PNG)

###### DecisionTreeRegressor
![19](https://user-images.githubusercontent.com/108620000/190868363-c10644f4-f017-4046-acff-90293865c16d.PNG)

###### RandomForestRegressor
![20](https://user-images.githubusercontent.com/108620000/190868364-2ad1222f-e2de-4c0c-9404-090961b9c5e3.PNG)

## Hyperparameter tuning 
![23](https://user-images.githubusercontent.com/108620000/190868456-18a4516c-a7d0-42fd-b5b1-b85f065bf093.PNG)

## Deploy the model with Flask
![26](https://user-images.githubusercontent.com/108620000/190868460-03aad9b5-8b96-4e12-9ff0-31d786ffc933.PNG)
