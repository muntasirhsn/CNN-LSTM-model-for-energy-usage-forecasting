# CNN-LSTM-model-for-energy-usage-forecasting
A CNN-LSTM encoder-decoder with univariate input is used to make multi-step predictions for time-series energy usage data
# Introduction 
Long Short-Term Memory or LSTM is a special type of Recurrent Neural Network (RNN) that can be used for time-series forecasting. LSTM networks are capable of learning features from input sequences of data and can be used to predict multi-step sequences. In this example, a CNN-LSTM architecture is used for multistep time-series energy usage forecasting. A one-dimensional convolutional neural network (1D CNN) is used to read and encode the input sequence. An LSTM network is then used as a decoder to make ode-step prediction for each value in the output sequence. For an excellent introduction to LSTMs, look up [Deep Learning for Time Series Forecasting](https://machinelearningmastery.com/deep-learning-for-time-series-forecasting/).
# Getting Started
The CNN_LSTM_univariate_multistep_output_github file is the main file for running the LSTM model. The publicly available time-series energy usage data of IIT, Delhi is sourced from [here](https://figshare.com/articles/dataset/Energy_dataset_of_IIITD/6007637/1). Infromation on the data can be found in this [article](https://www.nature.com/articles/sdata201915).

Note: The notebook files have been tested on Google Colab. 
# Model
The model is a CNN-LSTM architecture encoder-decoder architecture:
![image](https://github.com/muntasirhsn/CNN-LSTM-model-for-energy-usage-forecasting/assets/29087240/c2ecd128-a209-4a4b-ab7a-6e183865631a)
# Farecasting
Multi-step energy usage forecasting (12 weeks) with CNN-LSTM encoder-decoder model with a Root Mean Squared Error (RMSE) of 6.29.
![image](https://github.com/muntasirhsn/CNN-LSTM-model-for-energy-usage-forecasting/assets/29087240/835d43c9-331b-4bb4-876b-c20cac6a4066)
