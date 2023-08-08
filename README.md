# MNIST Digit Recognition using TensorFlow

This project demonstrates the training and evaluation of a neural network model for digit recognition using the MNIST dataset. The MNIST dataset is a widely used benchmark dataset for image classification tasks.

## Project Overview

This repository contains code for a simple neural network that learns to recognize handwritten digits from the MNIST dataset. The neural network architecture consists of a flattened input layer, a fully connected hidden layer with ReLU activation, and an output layer with softmax activation. The model is trained using the Adam optimizer and sparse categorical cross-entropy loss.

## How to Run the Code

1. Install the required libraries by running the following command:
   ```
   pip install tensorflow
   ```

2. Clone this repository:
   ```
   git clone https://github.com/yourusername/mnist-digit-recognition.git
   ```

3. Navigate to the project directory:
   ```
   cd mnist-digit-recognition
   ```

4. Run the provided Python script to train and evaluate the model:
   ```
   python mnist_digit_recognition.py
   ```

5. The script will load the MNIST dataset, preprocess the data, build the neural network model, compile it, train it on the training data, and evaluate its performance on the test data.

6. After the training is complete, the script will display the test accuracy of the trained model.

## Additional Notes

- The `MNIST.py` script contains comments explaining each step of the code for better understanding.
- You can modify the neural network architecture or training parameters in the script to experiment with different configurations.

## Requirements

- Python 3.x
- TensorFlow
- MNIST dataset (automatically downloaded and used by the script)

## Acknowledgments

This project is inspired by the MNIST dataset and aims to provide a basic example of digit recognition using a simple neural network architecture. It serves as a starting point for more complex image classification tasks.
