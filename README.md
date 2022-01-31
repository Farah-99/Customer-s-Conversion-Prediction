# <font color='blue'>Customer's Conversion Prediction: </font> 

Given various Information related to a customer’s behavior in online shopping websites,
I created a model that can predict whether that customer will generate revenue for the website's company or not. 
   => Binary Classification Problem
I Got the best results by using XGBoost with 96% accuracy; top 1 in Kaggle
---
 
* **Part 1 - Data Preprocessing**
   1. Importing libraries
   2. Importing the dataset
   3. Dataset information (Pandas Profiling)
   4. Dropping unnecessary columns
      - "Train" set
      - "Test" set
   5. Taking care of misssing data for "Train" and "Test" Data
      - 'Administrative'          
      - 'Administrative_Duration'
      - 'Informational'
      - 'Informational_Duration' 
      - 'ProductRelated' 
      - 'ProductRelated_Duration'
      - 'BounceRates'
      - 'ExitRates'
   6. Taking care of some outliers
   7. Encoding categorical data
      - 'Month'        
      - 'VisitorType'
      - 'Weekend'
      - 'OperatingSystems'
      - 'Browser'
      - 'Region
      - 'TrafficType'
   8. Spliting the Train & Test datasets
   9. Feature Scaling   
* **Part 2 - Training the Classification model**
   1. XGBoost
   2. Other algorithms
   3. Accuracy score  
* **Part 3 - Creating a submission.csv**
