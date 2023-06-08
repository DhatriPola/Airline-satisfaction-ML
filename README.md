# AirlineSatisfactionML
Predicting Satisfaction of  Airline Passengers #python
Research Outline

1. In this project, I understood the different factors affecting customer satisfaction in aviation. My aim is to develop a model that can predict a customer’s satisfaction level (Satisfied, Neutral/ Dissatisfied) based on data related to customer, trip and service features and identify which features contribute significantly to each group.

2. By analysing the importance of these features, we can then determine which trip and service features need to be improved to convert a First-time passenger into a returning passenger.

3. These insights can help airline executives working in Marketing/Sales/Customer Experience make data-driven decisions to improve customer satisfaction in the future. Data - using Kaggle Dataset on Airline Satisfaction published by TJ Klein. This clean dataset was originally taken from John D's Original Kaggle Dataset, published in 2018. The dataset contains 129880 observations for individual trips and consists of 24 columns/labels.

Model

1. The outcome variable is the Airline satisfaction level. Possible values : {Satisfied, Neutral or Dissatisfied}

2. We have 22 Explanatory variables that can be split into 3 categories:

Customer Features:
1. Age
2. Customer Type

Trip Features:
1.Type of Travel
2.Class
3.Flight distance
4.Departure/Arrival time convenient
5.Ease of Online booking
6.Gate location
7.Departure Delay in Minutes
8.Arrival Delay in Minute

Service Features
1. Inflight WiFi service
2. Food and drink
3. Online boarding 
4. Seat comfort 
5. Inflight entertainment 
6. On-board service 
7. Leg room service 
8. Baggage handling 
9. Check-in service 
10.Inflight service 
11.Cleanlines

I compared the performance of a simple Logistic model, XGBoost Model SHAP Analysis and Neural Network and test which features are recommended by each of these models.

Results: 
Based on the results of the XGBoost & Neural Network:
I prefer the XGBoost Model over the Neural network based on accuracy.
Airlines should highly focus on inflight wi-fi experience.
Satisfaction also depends on the minimizing travel delays.
Provide promotional offers to business travelers as they bring most business
Ease of online booking is important for all customers.
In the future, collect even more data to improve neural networks for both high precision and recall

