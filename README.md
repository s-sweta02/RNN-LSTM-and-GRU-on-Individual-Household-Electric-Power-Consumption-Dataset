# RNN-LSTM-and-GRU-on-Individual-Household-Electric-Power-Consumption-Dataset
Objective: To identify the dataset suitable for applying RNN, LSTM and GRU architectures. Compare the performance of these 3 architectures based on the objective metrics and analyse the performance.
Inference:  In this work,the base model of RNN, LSTM and GRU the batch size has been taken as 32 and time_steps as 30 and for the modified RNN, LSTM and GRU by increasing batch size to 128 and time_size is reduced to 10. In modified models the hyperparameter tuning is used and they are  dropout layer, early stopping and ReduceLROnPlateau.

The performance metrices used for comparing is MAE, MSE and RMSE. 
The base model performances were evaluated using MAE, MSE, and RMSE, where the RNN achieved MAE of 0.0921, MSE of 0.0452, and RMSE of 0.2126; the LSTM recorded MAE of 0.0767, MSE of 0.0418, and RMSE of 0.2044; and the GRU obtained MAE of 0.0811, MSE of 0.0424, and RMSE of 0.2060.

The modified model's performance metrics indicate that the RNN achieved MAE of 0.0223, MSE of 0.0016, and RMSE of 0.0404; the LSTM reported MAE of 0.2312, MSE of 0.1979, and RMSE of 0.4448; and the GRU recorded MAE of 0.2265, MSE of 0.1942, and RMSE of 0.4407.

The overall performance was shown by base model of LSTM. There is visible improvement in modified RNN as hyperparameter tuning has done.

