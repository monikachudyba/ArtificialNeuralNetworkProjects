# Artificial neural network practise

## AEC Employee Attrition
> Detection of outliers using fictional employees attrition dataset.
- data cleaning and exploration;
- Ouliers detection using Autoencoder, One-Class SVM and Minimum Covariance Determinant.

## CNN Coffee Bean Dataset
> Classification of roasting level based on coffee beans images as green, light, medium and dark.
- dimension reduction of images with PCA;
- data augmentation;
- classification using custom model of Convolutional Neural Network;
> Final accuracy: 97.50%
- classification using transfer learning: ResNet50 and EfficientNetB0 architectures;
> Final accuracy: 98.25% (ResNet)

## NLP Comments Generator
> Simple text generator based on comments from Polish Gossip Portal.
- web scraping using GraphQL;
- text processing (encoding, slicing, creating batches);
- evaluation of Recurrent Neural Network models with one GRU and two LSTM layers with tuned loss function;
- creating sample comments based on calculated models.

## RNN Economic Indicators
> Forecasting main economic indicators in Poland. 
- inflation data cleaning and exploration;
- evaluation of Recurrent Neural Network models with one SimpleRNN, one GRU and one LSTM layer; 
- values forecasting;
> Final coefficient of determination: 95.40% (SimpleRNN)
- Forecasting based on SARIMAX model;
> Final coefficient of determination: 94.51%
- outlier detection and imputation with Hampel filter;
- Forecasting based on XGBoost model;
> Final coefficient of determination: 96.80%
- unemployment rate data cleaning and exploration;
- evaluation of Recurrent Neural Network models with one SimpleRNN and forecasting;
> Final coefficient of determination: 96.25% 
- Forecasting based on SARIMAX models with and without exogenous variable - inflation;
> Final coefficient of determination: 94.35%
- Forecasting based on XGBoost model;
> Final coefficient of determination: 81.70%
