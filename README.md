# Stock Price Prediction using Multiple Models

This repository contains a Jupyter Notebook that implements time series forecasting for stock prices using three different models:

1. **LSTM (Long Short-Term Memory)**
2. **Prophet**
3. **ARIMA**

The notebook demonstrates how to collect stock price data, preprocess it, train the models, and evaluate their performance. Below are the performance metrics for each model:

---

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Models](#models)
4. [Performance Metrics](#performance-metrics)
5. [Results](#results)
6. [License](#license)

---

## Installation

To run this notebook, you need to install the required Python packages. You can do this by running the following command:

```bash
pip install numpy pandas yfinance tensorflow scikit-learn prophet pmdarima matplotlib
```

---

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Dikshitharyana/Stock_price_Prediction.git
   cd stock_price_prediction
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook Stock_Price_Prediction.ipynb
   ```

3. Run the notebook cells to execute the code.

---

## Models

### 1. LSTM (Long Short-Term Memory)
- **Description**: LSTM is a type of recurrent neural network (RNN) that is well-suited for time series forecasting.
- **Implementation**: The notebook includes data preprocessing, model building, training, and evaluation for LSTM.

### 2. Prophet
- **Description**: Prophet is a forecasting tool developed by Facebook that is designed for business time series data.
- **Implementation**: The notebook demonstrates how to prepare data, train the Prophet model, and make future predictions.

### 3. ARIMA
- **Description**: ARIMA (AutoRegressive Integrated Moving Average) is a statistical model used for time series forecasting.
- **Implementation**: The notebook uses `pmdarima` to automatically select the best ARIMA model parameters and make predictions.

---

## Performance Metrics

The performance of each model is evaluated using the following metrics:

### LSTM Performance Metrics:
- **Mean Squared Error (MSE)**: 19.79
- **Root Mean Squared Error (RMSE)**: 4.45
- **Mean Absolute Error (MAE)**: 3.51

### Prophet Performance Metrics:
- **Mean Squared Error (MSE)**: 50.72
- **Root Mean Squared Error (RMSE)**: 7.12
- **Mean Absolute Error (MAE)**: 6.42

### ARIMA Performance Metrics:
- **Mean Squared Error (MSE)**: 69.33
- **Root Mean Squared Error (RMSE)**: 8.33
- **Mean Absolute Error (MAE)**: 6.52

---

## Results

The notebook includes visualizations of the predictions made by each model:

- **LSTM Predictions vs Actual**: A plot comparing the actual stock prices with the predictions made by the LSTM model.
- **Prophet Model Forecast**: A plot showing the forecast made by the Prophet model.
- **ARIMA Forecast**: A plot showing the forecast made by the ARIMA model.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- **yfinance**: For fetching stock price data.
- **TensorFlow/Keras**: For implementing the LSTM model.
- **Prophet**: For providing an easy-to-use forecasting tool.
- **pmdarima**: For automating ARIMA model selection.

---

Feel free to contribute to this project by opening issues or submitting pull requests. Happy forecasting! 🚀
