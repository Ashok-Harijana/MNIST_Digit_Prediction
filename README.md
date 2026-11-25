MNIST Digit Recognition

# MNIST Handwritten Digit Recognition

## Project Overview

This project uses Deep Learning and TensorFlow to recognize handwritten digits (0–9) from the MNIST dataset.

The MNIST dataset contains 70,000 grayscale images of handwritten digits, each with a size of 28 × 28 pixels.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Deep Learning

## Dataset

The dataset is loaded directly from TensorFlow using:

`keras.datasets.mnist.load_data()`

- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28

## Project Workflow

1. Load the MNIST dataset.
2. Preprocess and normalize images.
3. Build an Artificial Neural Network (ANN).
4. Compile the model using Adam optimizer.
5. Train the model.
6. Evaluate model performance.
7. Visualize accuracy and loss.
8. Predict handwritten digits.
9. Save the trained model.

## Model Architecture

- Flatten layer
- Dense layer with 128 neurons (ReLU)
- Dense layer with 64 neurons (ReLU)
- Output layer with 10 neurons (Softmax)

## How to Run

Clone the repository:

`git clone YOUR_GITHUB_REPOSITORY_URL`

Install dependencies:

`pip install -r requirements.txt`

Run the Jupyter Notebook:

`jupyter notebook`

## Model Output

The model predicts handwritten digits from 0 to 9.

## Future Improvements

- Build a CNN model.
- Improve prediction accuracy.
- Create a Streamlit web application.

## Author
Ashok

Your Nme
