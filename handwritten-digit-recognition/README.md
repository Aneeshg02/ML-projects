# Handwritten Digit Recognition
## Description
This project builds an end-to-end machine learning pipeline to classify handwritten digits (0–9) using the MNIST dataset. It combines traditional machine learning (Logistic Regression) with deep learning (Convolutional Neural Networks) to compare performance and demonstrate the effectiveness of CNNs in image classification tasks.

## Dataset
This project uses the MNIST handwritten digits dataset. The dataset is automatically downloaded using built-in libraries. 
1. **Dataset**: MNIST (handwritten digits)
   from tensorflow.keras.datasets import mnist

  (x_train, y_train), (x_test, y_test) = mnist.load_data()

2. **Training samples**: 60,000
3. **Test samples**: 10,000
4. **Image size**: 28 × 28 (grayscale)

## Installation
git clone https://github.com/your-username/mnist-digit-recognition.git

## Install Dependencies
pip install -r requirements.txt

## How to Run
1. Open the Project Directory **cd mnist-digit-recognition**.
2. Open juypter notebook.
3. Open source code(ML-project.ipynb).
4. Run the every cell.
