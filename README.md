# UnemploymentRate_NeuralNetwork
Forecast Unemployment Rate in Indonesia  using Naive, Moving Average, Double  Exponential Smoothing, Time Series  Regression, ARIMA, and Neural Network


### Overview
Unemployment remains a pressing concern for 
economic planning and policy formulation in Indonesia. This 
study delves into analyzing biannually unemployment rate trends 
from 2013 to 2023, pivotal for addressing socio-economic 
challenges. Semi-annual data (February and August) sourced 
from the Central Bureau of Statistics is examined using various 
time series methods including Naive, Double Moving Average, 
Double Exponential Smoothing, Time Series Regression, 
ARIMA, and Neural Networks. Surprisingly, the Neural 
Network AutoRegressive (NNAR) model has a lag of 1 for 
autoregression and 1 hidden layer. NNAR(1,1) emerges as the 
champion. Its ability to capture intricate non-linear relationships 
leads to superior forecasting accuracy. These findings offer 
invaluable insights for stakeholders navigating Indonesia's 
economic landscape, guiding effective policies to combat 
unemployment and foster sustainable growth. In a world of 
uncertainty, harnessing advanced forecasting techniques like 
NNAR is key to shaping a brighter economic future for 
Indonesia


### Result
![image](https://github.com/user-attachments/assets/f509b266-0302-442e-98c1-1761031b8fad)


For the training data, the ARIMA(1,1,1) model 
demonstrated moderate accuracy with a RMSE of 0.3777, MAE 
of 0.2705 and MAPE of 3.5959. When applied to the testing 
data, the ARIMA(1,1,1) model yielded a RMSE of 0.99963, 
MAE of 0.8091, and MAPE of 12.8177. These results indicate 
that while ARIMA(1,1,1) is effective, its performance on the 
testing data shows room for improvement, particularly in terms 
of MAPE.
In comparison, the NNAR(4,5) model exhibited superior 
performance. For the training data, it achieved an MSE of 
0.282154, RMSE of 0.0796, MAE of 0.0573, and MAPE of 
0.9197, indicating an excellent fit. For the testing data, the 
NNAR(4,5) model continued to outperform ARIMA with a 
RMSE of 0.8238, MAE of 1.0130, and MAPE of 20.5614. 
Despite the higher MAPE compared to ARIMA on the testing 
data, the NNAR(4,5) model had lower MSE and RMSE values, 
suggesting it provides a more accurate overall forecast.
Other models, such as the Naive (Multiplicative), Double 
Exponential Smoothing (DES) methods, and Time Series 
Quadratic Regression, also showed notable results. The Naive 
model had an RMSE of 0.7631 for testing data, but has the 
highest errors on the training data. The DES model showed 
excellent performance on the training data with an RMSE of 
0.0513 but higher errors on the testing data. The Quadratic 
Regression has also promising results, but is unable to meet the 
assumptions. Thus, these three models are not good to forecast 
the biannually Unemployment Rate in Indonesia. 
Based on the comprehensive comparison, the NNAR(1,1) 
model emerges as the best-performing model. It offers the most 
accurate fit on the training data and achieves relatively low error 
metrics on the testing data, making it the most reliable model 
for forecasting the unemployment rate in this study. Here is the 
result of the forecasting using NNAR(1,1) 

![image](https://github.com/user-attachments/assets/e0bee392-6316-443e-b868-c327c5beb536)

##
