# Predicting customer buying behaviour  
### British Airways Project - Task 2  
Build a predictive model to understand factors that influence buying behaviour  


**Status**: Done  
**Dataset**: here  
**Jupyter notebook**:[here](https://github.com/IchfanKurniawan/british-airways-intern-project-customer-prediction/blob/master/code/british-airways-task-2.ipynb)

---  
---  

## <span id='all'> Summary</span>  
Two different machine learning methods used to train the given dataset. They are logistic regression & random forest. Here is the tabulation of all result:  

| Model      | AUC on CV | AUC on Test set |
| ----------- | :---------: | :---------: |
| logistic regression      | 0.7197       | 0.7196       |
| random forest   | 0.6872        | 0.6783        |

Note: AUC metric is used because of the imbalance target column which show that logistic regression performs better.  

Further analysis, the top predictors to class 1 from logistic regression model are the route of the flight (PEN, KUL, BKI, CGK) and want_baggage.

---  
---  
## <span id='all'>All about Projects</span>  
    
#### Project Context  
Customers are more empowered than ever because they have access to a wealth of information at their fingertips. This is one of the reasons the buying cycle is very different to what it used to be. Today, if you’re hoping that a customer purchases your flights or holidays as they come into the airport, you’ve already lost! Being reactive in this situation is not ideal; airlines must be proactive in order to acquire customers before they embark on their holiday.  

This is possible with the use of data and predictive models. The most important factor with a predictive model is the quality of the data you use to train the machine learning algorithms. For this task, you must manipulate and prepare the provided customer booking data so that you can build a high-quality predictive model.  

With your predictive model, it is important to interpret the results in order to understand how “predictive” the data really was and whether we can feasibly use it to predict the target outcome (customers buying holidays). Therefore, you should evaluate the model's performance and output how each variable contributes to the predictive model's power.  


#### Project Requirement   

1. Explore and prepare the dataset  
2. Train a machine learning model to predict the booking action from customer & find the most influential factors  
3. Evaluate model and present findings  

#### Project Planning  
1. Exploratory Data Analysis (EDA)
    - Data Structure Check (shape, datatype, head, tail)
    - Data Quality Check (missing value, outlier, distribution)
    - Data Cleaning (missing value, outlier, inappropiate values, high cardinality)
    - Content Investigation (hypothesis testing, predictive power check through descriptive/visualization and analytics)
2. Data Preporcessing & Feature Engineering
3. Feature Selection
4. Models Training
5. Models Evaluation  

#### Dataset Columns
Features: `num_passengers`, `sales_channel`, `trip_type`, `purchase_lead`, `length_of_stay`, `flight_hour`, `flight_day`, `route`, `booking_origin`, `wants_extra_baggage`, `wants_preferred_seat`, `wants_in_flight_meals`, `flight_duration`  

  
Target Column: `booking_complete`  

