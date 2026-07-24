# NVIDIA Stock Price Prediction

## Overview

This project predicts NVIDIA (NVDA) closing stock prices using
historical market data and a deep learning approach.

## Project Structure

```text
nvidia-stock-price-prediction/
│
├── P1_Prediksi_Close_Price_NVIDIA.ipynb    # Main notebook
├── NVIDIA STOCKS HISTORICAL DATA.csv       # Historical NVIDIA stock dataset
├── README.md                               # Project documentation
├── requirements.txt                        # Python dependencies
├── .gitignore                              # Git ignored files
└── LICENSE                                 # MIT License
```

## Dataset

-   Historical NVIDIA stock prices (CSV)
-   Features: Date, Open, High, Low, Close, Volume, Adjusted Close.

## Workflow

1.  Data preprocessing
2.  Exploratory Data Analysis (EDA)
3.  Data normalization
4.  Model training
5.  Prediction
6.  Evaluation (RMSE, MAPE)

## Tech Stack

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-learn
-   TensorFlow / Keras

## How to Run

``` bash
pip install -r requirements.txt
jupyter notebook
```

## Future Improvements

-   Hyperparameter tuning
-   Compare with LSTM, GRU, Transformer
-   Deploy with Streamlit
