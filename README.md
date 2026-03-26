# 🔐Problem Statement :

In service companies the major problem is customer retention.They do not know why their customers are  leaving .Due to this problem may the company get into losses.

# 🎯 Objective :

Build a Customer Churn Detection system by RandomForestClassifier model with pipeline struture.

# Data Set Over View : 

▶️Data set :Jio telecom company customers csv data set with  17000 records.

▶️features:customer name , age , gender , city , Monhtly charges , contract, Internet service , online security , churn

# Demo Results.
<img width="832" height="254" alt="Screenshot 2026-03-26 202110" src="https://github.com/user-attachments/assets/d0f7371d-b016-4d14-bf46-146469824f47" />


# Approach : 

➡️Here are the things I did while developing this model .

# 1-Importing Required Libraries 

# 2-Data collection and inspection() 
  pandas.read_csv(),df.info(),describe()
  
# 3-Data Preprocessing 

 3.1 Handling null values (fillna())
    
-3.2 Handling column types conversations 

# 4-EDA (Exploratory Data Analysis)

 ➡️Correlations between numerical columns
 
 ➡️Churn count yes vs no 
 
 ➡️Monthly charges vs churn
 
 ➡️Contract vs churn 
 
 ➡️Tenure vs churn
 
 ➡️ Internet service vs churn
 
 ➡️Online security vs churn 
 
# 5-Feature Engineering 

  5.1 Label Encoding,One Hot Coding
  
  5.2 Standard Scaling (To avoid confusion)
  
  5.3 Feature and Target selection 

# 6-Model Selection  
 
   model  (RandomForestClassifier)
   
# 7-Pipeline Buliding

  7.1Pipeline()
  
  7.2 Fitting(Training)
     
  7.3 Prediction 

# 8-Model Evaluation 
  Model generated  accuracy .

  Worked back on recall to generate accurate results by adjusting parameters.
  
  accuracy_score(), classification report (),classification matrix()

# 📈Impact of this System on business :

  Surely this model resuults can directly following places
  
  1-Churn risk can decrease ..

  2-Business revenue can boost

  3-Company growth can happen 


# By using this model we can rectify the churn rate along with overcoming the following things those making churn .

✔ Online Security

Customers without online security → higher churn

➡ Strong churn factor

✔ Monthly Charges

Churn customers pay more monthly

➡ Price sensitivity factor

✔ Contract

Month-to-month → highest churn

➡ VERY strong predictor

✔ Internet Service

Fiber optic → higher churn

➡ Possibly higher price / service issues

✔ Tenure

Low tenure → high churn

➡ New customers churn more

✔ Tech Support

No tech support → high churn

➡ Customer service impact

