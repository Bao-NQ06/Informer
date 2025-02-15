# Transformer Model for Time-Series Forecasting

## Overview

This project implements a Transformer-based model for time-series forecasting. The Transformer architecture, initially designed for NLP tasks, has been adapted to handle sequential data efficiently, making it suitable for time-series predictions. The model leverages self-attention mechanisms to capture dependencies across time steps effectively.

## Features

- Implements a Transformer-based architecture tailored for time-series forecasting.
- Uses positional encoding to handle sequential data.
- Supports multivariate and univariate time-series forecasting.
- Can handle long-term dependencies better than traditional RNN-based models.
- Customizable hyperparameters for tuning performance.

## Installation

### Requirements

Ensure you have the following dependencies installed. These are already included in the Jupyter Notebook:

- `torch`
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

### Clone the Repository

```bash
git clone https://github.com/Bao-NQ06/Informer.git
```

## Usage
### Data Preparation
The Jupyter Notebook contains all necessary steps to install and prepare the dataset automatically. Ensure your dataset is in the correct format within the notebook before proceeding.

### Training the Model
Run the Jupyter Notebook cells to train the model using the provided dataset.

### Evaluating the Model
To evaluate the trained model, execute the evaluation cells within the Jupyter Notebook.

### Inference
Use the trained model to make predictions by running the inference cells in the Jupyter Notebook.


## Model Architecture

- Embedding Layer: Converts input time-series data into dense representations.

- Positional Encoding: Adds sequence information to input embeddings.

- Multi-Head Self-Attention: Captures dependencies between time steps.

- Feedforward Layer: Applies transformations to extracted features.

- Output Layer: Generates time-series predictions

## Hyperparameters

- `num_layers:` Number of Transformer encoder layers.

- `d_model:` Dimensionality of input embeddings.

- `num_heads:` Number of attention heads.

- `dropout:` Dropout rate for regularization.

- `learning_rate:` Learning rate for optimization.

## Performance Metrics

- Mean Absolute Error (MAE)

- Mean Squared Error (MSE)

- Root Mean Square Error (RMSE)

- Mean Absolute Percentage Error (MAPE)

- Mean Squared Percentage Error (MSPE)

## References

- Vaswani et al., "Attention Is All You Need" (2017)

- Zhou et al., "Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting" (2021)

= Transformer models for time-series forecasting papers and implementations.
