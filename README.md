# Crypto-Prediction-2022-Project
Machine Learning  - Time Series - College Group Project - 2022
---

## Group
---
- Jonathan
- Jose
- Mario
- Willian

## Context
---
The following project is a 4th year student project about cryptocurrency prediction using
machine learning. 

We were planning to make predictions for digital currencies by implementing, evaluating and comparing different machine learning models. 
We have succeeded. At least we have managed to get good results overall.

## Used Models
---
- Prophet
- ARIMA
- LSTM
- Simple Exponential Smoothing

## Other Functionalities
---
Aside to the used models/implementations we have also added two extra functionalities.
- The Statistical Decision-making feature
- The Interactive Dashboard feature

### Statistical Decision-Making Feature
---
The statistical Decision-making feature is a custom made function created not to tell to the unsuspecting reader who put its hungry eyes on the results
presented here - so far - what to do with their money, but to help the minded, cognizant, and even
the investor-lover reader to make their own observations and help them to drive their very own future
strategic decision-making through the well based and researched demonstrated analysis.

It is based on the predicted close value of the next day, compared to the rules definied on the business case.
It returns a 'Sell' or 'Buy' "advice".

![Feature output](https://github.com/SergJohn/Crypto-Prediction-2022-Project/blob/main/imgs-project/stas-dec-feat.jpeg?raw=true)

### Interactive Dashboard
---
The Interactive Dashboard was created in order to display the findings and differences of the models on its results and caracteristics.

It returns the graphs of each model implementation, and the predicted value of a 'x' amount of days.

![Interactive Dashboard Main View, integrated within the statistical decision-making feature](https://github.com/SergJohn/Crypto-Prediction-2022-Project/blob/main/imgs-project/dash-main.jpeg?raw=true)

![Dash - graph and prediction view](https://github.com/SergJohn/Crypto-Prediction-2022-Project/blob/main/imgs-project/dash001.jpeg?raw=true)

![Dash - graphs comparison](https://github.com/SergJohn/Crypto-Prediction-2022-Project/blob/main/imgs-project/dash002.jpeg?raw=true)


## Real time Bitcoin API used
---
[bitpay](https://bitpay.com/api/)


## Notes
---
In order to attempt to achieve a more accurate results the next steps for the statistical decision would be to use a **multivariate multi-step Time Series Forecasting Model**
