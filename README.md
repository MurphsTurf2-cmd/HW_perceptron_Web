Perceptron Lab - ITS 365

Author: Noah Murphy

Project: L vs T Shape Classifier Overview

This lab is a basic implementation of a Perceptron to classify two shapes: L and T. The model is trained on a 4x4 grid (16 pixels). I trained the model in Python to find the weights and bias, then moved those parameters into a JavaScript web interface for live testing.

How it Works:

Training: I created a dataset of 100 samples in a Jupyter Notebook. This included the base L and T shapes, as well as shifted versions so the model isn't just looking for one exact pattern.

The Math: The code uses a basic activation function where any result ≥0 is a "T" (1) and anything else is an "L" (0).

Web UI: The website uses a 4x4 interactive grid. When you click "Predict," it multiplies your drawing by the trained weights, adds the bias, and outputs the result.
