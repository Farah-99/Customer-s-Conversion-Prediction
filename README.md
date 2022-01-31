# Customer-s-Conversion-Prediction

Given various Information related to a customer’s behavior in online shopping websites,
I created a model that can predict whether that customer will generate revenue for the website's company or not. 
=> Binary Classification ; I Got the best results by using XGBoost with 96% accuracy; 

Part 1 - Data Preprocessing
-Importing libraries
-Importing the dataset
-Dataset information (Pandas Profiling)
-Dropping unnecessary columns
  -"Train" set
  -"Test" set
-Taking care of misssing data for "Train" and "Test" Data
   'Administrative'
   'Administrative_Duration'
   'Informational'
   'Informational_Duration'
   'ProductRelated'
   'ProductRelated_Duration'
   'BounceRates'
   'ExitRates'
-Taking care of some outliers
-Encoding categorical data
   'Month'
   'VisitorType'
   'Weekend'
   'OperatingSystems'
   'Browser'
   'Region
   'TrafficType'
-Spliting the Train & Test datasets
-Feature Scaling

Part 2 - Training the Classification model
-XGBoost
-Other algorithms
-Accuracy score

Part 3 - Creating a submission.csv
