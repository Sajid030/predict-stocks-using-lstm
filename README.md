# Stock Price📈 Prediction using LSTM

![stock-price-importance](https://github.com/Sajid030/predict-stocks-using-lstm/assets/126476034/2b52b334-8b3f-4d0e-92a7-16cdbd0cb59f)

## Overview

This repository contains a Python notebook that demonstrates the process of predicting stock prices using Long Short-Term Memory (LSTM) networks. The notebook covers data preprocessing, exploratory data analysis, model training, and prediction for the next 10 days.

## About the Dataset

The dataset used for this project is the preprocessed CAC40 stock dataset. It includes historical stock price data for various companies listed in the CAC40 index. The dataset is provided in CSV format and contains columns such as 'Date', 'Open', 'High', 'Low', 'Closing_Price', and more.

## Requirements

To run the notebook successfully, ensure you have the following libraries and packages installed:

- `numpy`
- `pandas`
- `matplotlib`
- `mplfinance` (to visualize candlestick charts)
- `scikit-learn`
- `tensorflow` (for building and training the LSTM model)

You can install the required packages using the following command:

```
pip install numpy pandas matplotlib mplfinance scikit-learn tensorflow
```

## Notebook Contents

The notebook is structured as follows:

1. **Importing Libraries:** Loading the necessary libraries for data manipulation, visualization, and model training.

2. **Exploratory Data Analysis:** Preprocessing the dataset and performing visualizations to understand the stock price trends and patterns.

3. **Data Preprocessing:** Normalizing the data using MinMaxScaler and splitting it into training and testing sets.

4. **LSTM Model Training:** Building an LSTM model with multiple layers and training it on the prepared data. Utilizing callbacks for model checkpointing and early stopping.

5. **Model Evaluation:** Evaluating the trained model's performance on both training and testing data using RMSE (Root Mean Squared Error).

6. **Predicting Next 10 Days:** Using the trained model to predict stock prices for the next 10 days based on the last sequence of data.

7. **Visualization:** Visualizing the predicted stock prices for the next 10 days using a line plot.

## Acknowledgments

This project is part of the TechnoHacks Virtual Internship Program August Batch 2023. Special thanks to the program organizers for providing this opportunity to enhance my data science skills.

