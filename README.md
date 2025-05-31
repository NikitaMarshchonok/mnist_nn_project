# MNIST Handwritten Digit Classification Project

This project demonstrates the implementation of a simple neural network (MLP) to classify handwritten digits from the MNIST dataset. It covers data preparation, model creation, training, evaluation, and saving.

## Project Overview

We used the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9). The images were preprocessed, normalized, and fed into a neural network with one hidden layer of 128 neurons.

## Model Architecture

- Input Layer: 784 neurons (flattened 28x28 image)
- Hidden Layer: Dense layer with 128 neurons, ReLU activation
- Output Layer: Dense layer with 10 neurons (one for each digit), softmax activation

The model was trained for 5 epochs.

## Final Performance

- Final test accuracy: **~91.5%**

## Visualizations

Here’s a look at the final confusion matrix and the training/validation accuracy curves:

### Final Confusion Matrix
![Confusion Matrix](images/1.png)

### Accuracy Curves
![Accuracy Curves](images/2.png)

## Installation

Clone the repository and install dependencies:
```bash
git clone 
cd repo
pip install -r requirements.txt


Running the Project
Open the Jupyter Notebook to run the code:
jupyter notebook

The main steps in the notebook include:
Loading and visualizing the MNIST data
Preprocessing the data (flattening and normalizing images, one-hot encoding the labels)
Building and compiling the MLP model
Training and evaluating the model
Saving the trained model (mnist_mlp_model.h5)
Plotting performance metrics (accuracy, confusion matrix)

Files in this project
mnist_nn_project.ipynb — Jupyter notebook with complete workflow
mnist_mlp_model.h5 — Saved Keras model
requirements.txt — List of Python dependencies
images/ — Folder with screenshots of the confusion matrix and accuracy curves

Requirements
All required Python libraries are listed in requirements.txt and include:
tensorflow
keras
numpy
matplotlib
seaborn
scikit-learn

License
This project is open-source and free to use for learning purposes.
