# WindTurbine-AnomalyPrediction-DL

This repository contains the code and resources for my Biggest Project on wind turbine anomaly prediction using deep learning techniques. The main focus is on predicting anomalies in wind turbines by leveraging U-Net and LSTM architectures, along with baseline studies using LSTM and ConvLSTM models.

## Project Overview

This project is a completely experimental research endeavor focused on exploring innovative methods for anomaly prediction in wind turbines using deep learning.

The goal of this project is to develop a system capable of early detection of anomalies in wind turbines using SCADA data. This is achieved by combining several neural network architectures, including:

U-Net + LSTM: A hybrid model designed for anomaly detection in time series converted to images.
Baseline LSTM: Initial LSTM models, including both non-stateful and stateful versions, used for sequence prediction tasks.
ConvLSTM: A more experimental approach that integrates convolutional operations into the LSTM structure for spatial-temporal data handling.

## Motivation
The maintenance of wind turbines is crucial for ensuring operational efficiency and avoiding unexpected failures. Using data-driven anomaly prediction methods can help in early failure detection, minimizing downtime and repair costs. This project explores various deep learning models, especially focusing on transforming time-series data into image-like representations to take advantage of convolutional architectures.

## Objectives
Data Processing: SCADA data from wind turbines is transformed into image-like formats using sliding windows over time series data.
U-Net Implementation: U-Net is employed for automatic labeling and feature extraction from the generated images.
Hybrid Model: U-Net's outputs are integrated with LSTM for sequence prediction to improve anomaly detection accuracy.
Baseline Studies: Initial evaluations using standard LSTM models to establish a baseline for comparison.
ConvLSTM Exploration: A novel preprocessing approach that integrates convolutional layers with LSTM, enabling efficient processing of both spatial and temporal information.

## Models Implemented
1. U-Net + LSTM
A combination of U-Net for feature extraction and LSTM for sequential anomaly prediction.
Suitable for datasets transformed from time series to image-like structures.
2. Baseline LSTM
- Non-Stateful LSTM: A standard LSTM model for sequential prediction without maintaining states across batches.
- Stateful LSTM: A stateful LSTM model that maintains states, providing better performance on longer sequences.
3. ConvLSTM: A convolutional LSTM model designed for spatial-temporal data. This approach is aimed at improving the anomaly detection capabilities by using both convolutional and recurrent layers.
