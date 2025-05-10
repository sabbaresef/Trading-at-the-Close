# Optiver - Trading at the Close

## Description
This repository contains the code for the Kaggle competition [Optiver - Trading at the Close](https://www.kaggle.com/competitions/optiver-trading-at-the-close).

It reached the bronze medal and position 315 in the final ranking, calculated based on the hidden test set.

The code is developed by Francesco Sabbarese and is based on boosting algorithms, like XGBoost and Lightgbm, and a strong features engineering phase to exploit temporal component. 

You can also find a version that is based on Recurrent Neural Network and Tensorflow, and another version in which data are first clustered and than a regressor based on boosting algorithm is applied on each cluster. 


## The Challange 
Stock exchanges, like the Nasdaq, are fast-paced environments where every second counts, with heightened volatility in the final minutes of trading. The Nasdaq Closing Cross auction sets the official closing prices, which are key indicators for market participants. Optiver, a global electronic market maker, plays a significant role by offering competitive prices across various financial instruments.

During the last ten minutes of trading, market makers like Optiver combine order book and auction data to provide optimal prices. The challenge here is to develop a model that predicts closing price movements using this combined data, helping improve market efficiency. This task mirrors the real-world data science challenges faced by traders and researchers at Optiver.

## Setup 
If you run the code on Kaggle notebook all packages are already installed in the environment.




