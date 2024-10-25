# Handwrittenimages
Image Classification of Digital Handwritten Digits using MNIST dataset
- This project focuses on classifying handwritten digits using the MNIST dataset
- It provides a step-by-step guide to develop, evaluate, and improve convolutional deep learning neural networks for image classification.
- The repository includes code for developing a robust test harness, exploring model improvements.

# Requirements
- Python 3.5 +
- Scikit-Learn (latest version)
- Numpy (+ mkl for Windows)
- Matplotlib

# To the get the date for this project please follow the below code:

from tensorflow.keras.datasets import mnist
(x_train, y_train), (x_test, y_test) = mnist.load_data()
