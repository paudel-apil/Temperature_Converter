# Celsius to Fahrenheit Converter (TensorFlow)

This is a simple machine learning model built using TensorFlow and Keras to convert temperatures from Celsius to Fahrenheit.

## Overview

The model is a basic neural network with a single dense layer. It learns the linear relationship between Celsius and Fahrenheit:

F = (C × 9/5) + 32

## Model Architecture

* One input neuron (Celsius)
* One output neuron (Fahrenheit)
* Fully connected (`Dense`) layer

## Training Details

* Loss function: Mean Absolute Error (MAE)
* Optimizer: Adam (learning rate = 0.1)
* Epochs: 500
* Metrics: Accuracy (note: not very meaningful for regression tasks)

history = model.fit(X_train, y_train, epochs=500, verbose=0)
```

## Usage

1. Prepare training data (`X_train`, `y_train`) with Celsius and corresponding Fahrenheit values.
2. Train the model using the code above.
3. Use `model.predict()` to convert new Celsius values to Fahrenheit.

## Notes

* This is a simple demonstration of linear regression using neural networks.
* A neural network is overkill for this problem, but useful for learning basics of TensorFlow.
