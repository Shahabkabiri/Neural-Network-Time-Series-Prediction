# Neural Network Time Series Prediction

This Python script is designed for time series prediction using neural networks. It includes functions for data downloading, model setup, and prediction based on specified parameters. The script can be used to create, train, and evaluate multiple neural network models for time series data.

## Prerequisites

- Python
- MetaTrader 5 terminal installed and running (for data downloading)
- Required Python packages (e.g., pandas, MetaTrader5, joblib, scikit-learn)

## Usage

1. Clone this repository or download the script.
2. Install the required Python packages using `pip install -r requirements.txt`.
3. Customize the script by specifying the model parameters in the `All` list.
4. Run the script using `python script_name.py`, where `script_name.py` is the name of your script.

## Description

This script provides functions for the following tasks:
- Creating folders for storing model parameters, source data, joblib files, and more.
- Generating filenames for model parameters and saving them to the `/Parameters/` folder.
- Determining the time shift based on the specified parameters.
- Downloading historical data from MetaTrader 5 for model training.
- Normalizing the downloaded data and splitting it into training and testing sets.
- Building and training a neural network using scikit-learn's MLPRegressor.
- Saving the trained neural network model to the `/Joblib/` folder.
- Performing time series prediction based on the trained models.
- Updating and saving the model counter to keep track of models.

You can customize the parameters, timeframes, and other settings according to your specific use case.

## License

This project is licensed under the [MIT License](LICENSE).
