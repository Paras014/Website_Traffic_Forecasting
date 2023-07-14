# Website_Traffic_Forecasting
Predicting future number of sessions of website using Time Series Forecasting
# Dataset Link - 
https://www.kaggle.com/datasets/kajal1/web-traffic-forecast-dataset?group=owned
# Model architecture - 
<br>

| Layer         | Output Shape  | Parameters |
| ------------- | ------------- | ---------- |
|Conv1D  | (None, 166, 64)  |      256       |
| Bidirectional LSTM | (None, 166, 32) |   20608    |
| LSTM |  (None, 166, 32) | 20608 |
|LSTM | (None, 20)| 4240 |
| Dense | (None, 10) | 210 |
| Dense | (None, 1) | 11 |

--------------------------------------------------------
Total params: 91,373 <br>
Trainable params: 91,373 <br>
Non-trainable params: 0 <br>
