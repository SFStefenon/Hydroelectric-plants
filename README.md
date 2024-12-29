# Hydroelectric-plants

This repository presents a multi-criteria optimization strategy for model and filter selection applied to improve the management of hydroelectric power plants.
The strategy considers the Optuna based on a tree-structured Parzen estimator to select the predictor and the filter for the time series.

The standard recurrent neural network (RNN), dilated RNN, long short-term memory (LSTM), temporal fusion transformer (TFT), temporal convolutional neural (TCN), deep non-parametric time series forecaster (DeepNPTS), neural basis expansion analysis for time series forecasting (N-BEATS), and neural hierarchical interpolation for time series forecasting (NHITS) models were considered.

The Christiano Fitzgerald, Hodrick-Prescott, season-trend decomposition using locally estimated scatterplot smoothing (LOESS), and multiple season-trend decomposition using LOESS filters are evaluated. 

The study considers the inflow data from the Belo Monte dam in Brazil. For comparison purposes, daily measurements are considered for the period from December 2021 to December 2024, resulting in 1,095 observations considering three years of 365 days. The dataset is available [here](), for analysis of other power plants' further evaluations or comparisons can be made based on the [original dataset](https://dados.ons.org.br/dataset/dados-hidrologicos-res).









