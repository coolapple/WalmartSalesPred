# Walmart Sales Forecasting Data Science Project

Accomplished business problem:
We are predicting the Walmart sales for different departments of 45 Walmart stores by applying multivariate linear regression techniques with 3 years of dataset. Due to the trend, seasonality, and auto correlations of the train data set, we feature engineering our dataset to apply the linear regression techniques. Overall, we achieved R square of 87% on both the train set and test set. We also investigate the impact of both external and internal factor impacts on the Walmart sales projection. 
Steps for the implementation:
1.	Integrated data from multiple AWS SQL tables. 
2.	Amputated missing values using 0 for mark down1-5 and mean values for CPI and unemployment. 
3.	Reengineering new holiday variable for pre-thanksgivings and pre-Christmas due to sale spikes. 
4.	Rolling mean and variance of store sales stabilize after removing pre-Thanksgiving and pre-Christmas.
5.	Decompose data into trend, seasonality and residuals. 
6.	Start to apply linear regression model from simple time, month, difference, macro variables to markdown1-5. 
7.	Overall, we achieved a 87% R square on both training and test set. 
