# Using LSTM RNNs to predict sepsis from clinical data
![image](https://github.com/radimurban/sepsis-prediction/assets/78273894/b8d62c10-283b-4412-868d-581afde70830)

LSTM-RNN-based model using time-series of clinical data measurements for early detection of the condition.

Unlike traditional feedforward neural networks, which process fixed-size inputs independently, recurrent neural networks (RNNs) are designed to handle sequences of variable length. This makes them particularly useful for tasks involving time-series data or natural language processing. I have recently come across The PhysioNet/Computing in Cardiology Challenge 2019 where the goal is to come up with a model that is able predict the probability of sepsis (life-threatening condition that occurs when the body's response to infection causes organ failure, or death) based on the past clinical data measurements. We are given a time-series dataset of 20 thousand files containing hourly measurements of roughly 42 variables per patient. For purposes of this mini-project, we will try to predict the sepsis condition within the next hour based on past 10 hourly measurements. We have to preprocess the data, construct the dataset, design the model, train it and finally evaluate it. You can find the complete notebook here and steps of implementation [here](https://www.radimurban.com/blog/rnn-to-predict-sepsis/).


