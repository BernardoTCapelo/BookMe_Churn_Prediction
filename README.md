# BookMe_Churn_Prediction
## Introduction
The BookMe company operates in the hospitality sector, providing accommodation to tourists and travellers, delivering necessary lodging services to those who travel the world, whether for leisure or business. It provides an international website where citizens can book their accommodation. Presently they have around 30,000 registered customers and serve more than 100,000 consumers a year. The website offers a variety of services, but they are focused in providing rooms with the best conditions possible. In order to control the quality of the services, every time a client makes a reservation, at the
end of the stay, a survey is sent to complete on how the guest perceived the provided services. 
A scale of 0 to 5 is used to rate multiple aspects of the services, in this way, customers can reveal how satisfied they are regarding location, price, amenities provided, and others.
Focused in detecting possible churn situations, BookMe hired a team of data scientists (your group) to analyze the behavior and satisfaction of their customers and to predict which customers have a high probability of churn depending on their behavior/satisfaction.

## Table of Contents
* Project Objectives
* Dataset
* Predictive Models
* Project Status

## Project Objectives
The goal of this project was to build a predictive model that answers the question “Which customers are more likely to churn?” using the small quantity of data accessible from the customers database that contains general information about the customers behaviour and their satisfaction. The chosen predictive models must be from scikit-learn package.

## Dataset
* The training set should be used to build your machine learning models and
assess their performance if needed. In this set, you also have the ground truth
associated with the customer behavior, i.e., if the user was considered churn or
not.
* The test set should be used to see how well your model performs on unseen
data. In this set, you don’t have access to the ground truth, and the goal of
your team is to predict that value (0 or 1) by using the model you created based
on the training set. The predicted values in the test set should be submitted
on Kaggle. The score of your predictions will be evaluated using the F1 Score.

The available data contains the following attributes:
* Cust ID - Customer’s identification number
* Name - Customer’s name
* Year Birth - Customer’s birth year
* Longevity - Whether the customer registered more than 1 year ago or not (yes or no)
* Churn - Whether the customer churned or not (churn - 1; or nochurn - 0)
* TypeTravel - Customer’s reason for travelling (business or leisure)
* RoomType - Type of room reserved
* RewardPoints - Customer’s rewarding point for loyalty
* Comfort - Satisfaction level of customer regarding comfort of the room (0 to 5)
* ReceptionSchedule - Satisfaction level of customer regarding reception schedule (0 to 5)
* FoodDrink - Satisfaction level of customer regarding food and drink available (0 to 5)
* Location - Satisfaction level of customer regarding accommodation location (0 to 5)
* Wifi - Satisfaction level of customer regarding wi-fi service (0 to 5)
* Amenities - Satisfaction level of customer regarding accommodation amenities (0 to 5)
* Staff - Satisfaction level of customer regarding staff (0 to 5)
* OnlineBooking - Satisfaction level of customer regarding online booking ease (0 to 5)
* PriceQuality - Satisfaction level of customer regarding price quality relationship (0 to 5)
* RoomSpace - Satisfaction level of customer regarding room space (0 to 5)
* CheckOut - Satisfaction level of customer regarding check-out (0 to 5)
* CheckIn - Satisfaction level of customer regarding check-in (0 to 5)
* Cleanliness - Satisfaction level of customer regarding cleanliness (0 to 5)
* BarService - Satisfaction level of customer regarding bar service (0 to 5)

## Predictive Models
The predictive models tested in this model where:
* Logistic Regression
* Random Forest Classifier
* KNN Classifier
* Decision Tree Classifier
* Neural Network (MLP) Classifier
* Gradient Boosting Classifier
According to the obtained results for each model, the best model is either Random Forest Classifier or Gradient Bossting Classifier.

## Project Status
Finished.
