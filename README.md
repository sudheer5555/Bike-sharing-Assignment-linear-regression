# Bike Sharing demand prediction
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
# Business Goal
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
# Data preparation
Converted some variables(season,weather situation,month,weekday) are categorical strings and then converted dummy variables.There are no oultiers and dummy variables to handle. Used MinMax scaler method to convert the continuous variables(humidity,temparature,windpeed) to same scale(0,1).
# Model building
We build the linear regression. with help of RFE select some features and used statsmodel to filter out some more features.
# Conclusion
Year, weather situation , temperature , months(jul,nov) , weekday(sat) plays an important role in predicting the bke sharing demand.
