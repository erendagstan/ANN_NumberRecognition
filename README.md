# ANN Project with TensorFlow

This project implements an Artificial Neural Network (ANN) using TensorFlow for recognizing handwritten digits from the MNIST dataset. The ANN is trained to classify images of handwritten digits into one of the ten classes (0 to 9).

## Prerequisites

Make sure you have TensorFlow installed. If not, you can install it via pip:

```bash
pip install tensorflow
````
# Getting Started
1. <b>Importing Libraries:</b> Import necessary libraries including TensorFlow, Matplotlib, and NumPy.
2. <b>Loading Data:</b> Load the MNIST dataset using tensorflow.keras.datasets.mnist.
3. <b>Data Analysis:</b> Analyze the loaded data to understand its structure and visualize a few samples.
4. <b>Data Preprocessing:</b><ul>
   <li>Encode target variables using one-hot encoding.</li>
   <li>Reshape input data to the required format.</li>
   <li>Normalize input data to a range of [0, 1].</li></ul>
5. <b>Modeling:</b><ul>
   <li>Design the ANN model using TensorFlow's Sequential API.</li>
   <li>Compile the model with appropriate loss function, optimizer, and evaluation metrics.</li></ul>
6. <b>Model Training</b>: Train the model on the training data.
7. <b>Model Evaluation:</b> Evaluate the trained model on the test data.
8. <b>Performance Analysis:</b> Analyze the model's performance by visualizing training and validation metrics.
