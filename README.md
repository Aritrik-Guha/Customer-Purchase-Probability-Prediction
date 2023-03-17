# Customer-Purchase-Probability-Prediction
Predicting probability of customers buying any product in a 1-month time period 
Applied RFM analysis to understand behaviour of customer purchase of a period of time.
Applied transformation over RFM values to reduce spread and effect of outliers.
Applied quantile bucketing to get scores of RFM metrics.
Applied weighted scoring technique to find net RFM score.
Used net_RFM_SCORE as an input feature to the model wherein the target was a column stating if customer has purchased next month(1) or not(0)
Prepared prediction set considering entire data, while excluded last 1 month of data for preparing model training and validation data
