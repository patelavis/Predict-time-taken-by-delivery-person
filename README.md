# Predict-time-taken-by-delivery-person
The company wants to improve its system that calculates ETA for delivery persons. Rather that relying on some fixed method/formula. The management has decided to develop intelligent software that can predict the time of arrival for the delivery persons.
## Task
Develop a machine learning model that can calculate the time taken by the delivery person to deliver the order, given relevent information.
## Dataset description
Train - 45593
Test - 11399

|Columns_Name|                   Details|
|----------:|:-------------------------|
|ID|                             Represent a unique identification of an entry.|
|Delivery_person_ID|             Represent a unique identification of a delivery person.|
|Delivery_person_Age|            Represent the age of a delivery person|
|Delivery_person_Ratings|        Represent the average ratings given to the delivery person. (1 to 5)|
|Restaurant_latitude|            Represent the latitude of the restaurant.|
|Restaurant_longitude|           Represent the longitude of the restaurant.|
|Delivery_location_latitude|     Represent the latitude of the Delivery location.|
|Delivery_location_longitude|    Represent the longitude of the Delivery location.|
|Order_Date|                     Represent the date when the order was placed.|
|Time_Ordered|                    Represent the time when the order was placed.|
|Time_Order_picked|              Represent the time when the order was picked from the restaurant.|
|Weather conditions|             Represent the weather conditions (windy, sunny, cloudy, stormy, fog, sandstorms, etc.)|
|Road_traffic_density|           Represent the road traffic density (Jam, High, Medium and Low)|
|Vehicle_condition|              Represent the condition of the Vehicle. (Smooth, Good or Average)|
|Type_of_order|                  Represent the type of order (Snack, Meal, Buffet, Drinks, etc.)|
|Type_of_vehicle|                Represent the type of vehicle one is using (Motorbike, Bicycle etc.)|
|multiple_deliveries|            Represent the number of orders to be delivered in one attempt.|
|Festival|                       Represent whether day is festive or not.|
|City|                           Represent the city|
|**Time_taken (min)**|               **Represent the time taken by the delivery person to deliver the order. [TARGET]**|
