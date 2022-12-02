# comp5513PolyUFintechBull_Model4
COMP5513 PolyU Fintech Bull Model #4 Source Code

Stock Price Prediction

The full name of Model 4 is 6Xs-by-3Ys Linear Regression , powered by TensorFlow. We assigned a short form for this model : 6to3LR. Linear Regression is adopted in Model 4 (i.e. 6to3LR) for machine learning. The dataset adopted is Yahoo Finance HK#2800 Historical Data. The training period is Jan/02/2009 – Dec/31/2019; while the Testing / Prediction Period is Jan/02/2020 – Sep/30/2022.

The model takes reference from six features of hk#2800 and treat the historical next-day prices , next-six-month-prices and next-year prices as the training labels (period : Jan/02/2009 – Dec/31/2019). The six features being used are 'Today Close Price (CP)' , 'EMA_10Days' , 'SMA_120Days' , 'RSI-12Days' , 'Positive Volume Index (PVI)' and 'Negative Volume Index (NVI)'. 

Then, powered by Linear Regression of TensorFlow, the model (i.e. 6to3LR) are being built and trained; and aims at predicting the labels of next-day prices , next-six-month prices and next-year prices(period : Jan/02/2020 – Dec/31/2022).

