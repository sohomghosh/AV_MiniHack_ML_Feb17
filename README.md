Solutions to Mini-Hack organised by Analytics Vidhya (https://datahack.analyticsvidhya.com/contest/minihack-machine-learning/)

Problem Statement
Build a predictive model, which could help a cab lending company in predicting the surge_pricing_type pro-actively. This would in turn help them in matching the right cabs with the right customers quickly and efficiently.

Data
Variable Definition
Trip_ID ID for TRIP (Can not be used for purposes of modelling)
Trip_Distance The distance for the trip requested by the customer
Type_of_Cab Category of the cab requested by the customer
Customer_Since_Months Customer using cab services since n months; 0 month means current month
Life_Style_Index Proprietary index created by Sigma Cabs showing lifestyle of the customer based on their behaviour
Confidence_Life_Style_IndexCategory showing confidence on the index mentioned above
Destination_Type Sigma Cabs divides any destination in one of the 14 categories.
Customer_Rating Average of life time ratings of the customer till date
Cancellation_Last_1Month Number of trips cancelled by the customer in last 1 month
Var1, Var2 and Var3 Continuous variables masked by the company. Can be used for modelling purposes
Gender Gender of the customer
Surge_Pricing_Type Predictor variable can be of 3 types

Note:
1. Evaluation Metric is accuracy i.e. percentage of Surge_Price_Category you correctly predict.
2. You are expected to upload the solution in the format of "sample_submission.csv"
3. Public and Private split is 25:75
