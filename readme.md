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
git clone https://github.com/your-repo/transformer-timeseries.git
cd transformer-timeseries
