# Amazon Stock Price Prediction using RNN

This project implements a Recurrent Neural Network (RNN) to predict Amazon stock prices based on historical data.

## Table of Contents
1. Overview
2. Requirements
5. Project Structure
6. Model Architecture
7. Results
8. License

## Overview

This project uses Long Short-Term Memory (LSTM) networks, a type of RNN, to predict Amazon stock prices. It includes data collection, preprocessing, model training, prediction, and evaluation steps.

## Requirements

- Python 3.7+
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Project Structure

- `stock_data_prediction.ipynb`: Main script containing the entire workflow
- `README.md`: This file
- `requirements' : List of required Python packages

## Model Architecture

The RNN model consists of:
- Two LSTM layers with 50 units each
- Dropout layers (20% dropout rate) for regularization
- A Dense output layer

The model is compiled with Adam optimizer and Mean Squared Error loss function.

## Results

- Mean Squared Error: 521.7324306772398
- Mean Absolute Error: 21.109838960166766
- Root Mean Squared Error: 22.84146297147448


## License

This project is open source and available under the [MIT License](LICENSE).
