#problem statement 
In service companies the major problem is customer retention.they do not know why their customers are  leaving..

🎯 Objective 
Built a Customer Churn Detection system

#▶️Data set :Jio telecom company customers csv data set with  17000 records.

➡️here are the things I did while developing 
1-Importing libraries 
2-Data collection and inspection(pd.read_csv(),.info())
3-Data preprocessing 
    3.1 Handling null values (fillna())
    3.2 Handling column types conversations 
➡️EDA 
     ➡️ Correlations between numerical columns
     ➡️Churn count yes vs no 
     ➡️Monthly charges vs churn
     ➡️Contract vs churn 
     ➡️Tenure vs churn
     ➡️ Internet service vs churn
     ➡️Online security vs churn 
4-Feature Engineering 
     4.1 Label Encoding,One Hot Coding
     4.2 Standard Scaling (To avoid confusion)
     4.3 Feature and Target selection 
5-Modeling 
     5.1 model selection
     5.2 Fitting(Training)
     5.3 Prediction 
6-Evaluation 
     accuracy_score(), classification report .

📈Usage of this model:
    -Customer retention programs 
    -Revenue growth
    -predictions of  new customers churn
    -Company growth 

By using this model we can rectify the churn rate along with overcoming the following things those making churn .

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

#Impact of this System on business 
1-Churn risk can decrease ..
2-Business revenue can boost
3-Company growth can happen 
