# Food Cost Prediction Hackathon - Machine Hack powered by Analytics India Magazine

#### The work here include the regression model to predict the food cost across restaurants from the given data. For details about the problem statement below.

#### Problem Statement 

Who doesn’t love food? All of us must have craving for at least a few favourite food items, we may also have a few places where we like to get them, a restaurant which serves our favourite food the way we want it to be. But there is one factor that will make us reconsider having our favourite food from our favourite restaurant, the cost. Here in this hackathon, you will be predicting the cost of the food served by the restaurants across different cities in India. You will use your Data Science skills to investigate the factors that really affect the cost, and who knows maybe you will even gain some very interesting insights that might help you choose what to eat and from where.

Size of training set: 12,690 records

Size of test set: 4,231 records

FEATURES:
TITLE: The feature of the restaurant which can help identify what and for whom it is suitable for.

RESTAURANT_ID: A unique ID for each restaurant.

CUISINES: The variety of cuisines that the restaurant offers.

TIME: The open hours of the restaurant.

CITY: The city in which the restaurant is located.

LOCALITY: The locality of the restaurant.

RATING: The average rating of the restaurant by customers.

VOTES: The overall votes received by the restaurant.

COST: The average cost of a two-person meal.



#### Implementation

##### Step 1: Data preprocessing for the given data which includes removing null values, data type casting and label encoder for categorical values

##### Step 2: Feature Engineering which identifies majorly impacting variables from the data on the dependent one
##### Step 3: Data is feed to the random forest regressor, the results seems satisfactory but can be improved with proper tuning
##### Step 4: Gradient Boosting Model provides some level of accuracy but I tried comparing that with XGB model and it seems to perform extremely well and improves the accuracy when compared to the other two ones.


###### For further reading - XGB model in depth for these kinda problems