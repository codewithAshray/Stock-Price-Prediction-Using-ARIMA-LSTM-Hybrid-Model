# Time Series Analysis Using ARIMA-LSTM-Hybrid-Model

# Introduction

Time series exploration is a very important area of data analysis, extracting knowledge from past observations to identify the evolution of a phenomenon in the present and facilitate its projection into the future.

One of the most famous and popular models for this type of analysis is the ARIMA model. The popularity of this model comes mainly from its flexibility, quality and versatility. It is available for autoregressive processes (AR), moving average processes (MA) and the combination of the two (ARMA). ARIMA operates on processes that are called stationary, but can adapt to processes that are not in its integrated version (The "I" in ARIMA).

Another famous model is Neural networks that outperform traditional statistical models, whether it is a question of regression, classification or more advanced problems when we have very massive amount of data.The particularity of neural networks is their tendency to adapt to the features created by the data or rather able to learn the distribution itself. Neural Networks are also available in several architectures like RNN, CNN, DQN, GAN each corresponding to a particular type of problem.

In this repository I tried to couple the effect of these two model to produce a result that could exceed the individual performance of each model.Combining the two would help us to capture certain patterns that would be inaccessible to one of the two models 

# Model Description

ARIMA Model (Autoregressive Integrated Moving Average)

  ARIMA was first introduced by Box and Jenkins in 1976. ARIMA characterizes time series by going from three fundamental aspects:
  - Autoregressive terms (AR) that model past process information.
  - Integrated terms (I) that model the differences needed to make the process stationary.
  - The moving average (MA) that controls the past information of noise around the process.

LSTM Model (Long Short Term Memory)

  LSTM networks are a type of recurrent neural network capable of learning order dependence in sequence prediction problems. This is a behavior required in complex problem domains   like machine translation, speech recognition, and more. LSTMs are a complex area of deep learning.
