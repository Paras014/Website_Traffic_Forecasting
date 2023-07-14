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
# Results - 
## Test set forecats
![Full_test](https://github.com/Paras014/Website_Traffic_Forecasting/assets/98278584/c07722b7-2c80-4317-a7ae-136fea44f0df)
<br>
## 1 week forecast
![168test](https://github.com/Paras014/Website_Traffic_Forecasting/assets/98278584/8dbfd4f6-eddd-4496-a6f7-01e057b7dd5d)
<br>
## 1 day forecast
![24test](https://github.com/Paras014/Website_Traffic_Forecasting/assets/98278584/591df582-bbd8-4f56-b2e4-0e277c38e21b)
