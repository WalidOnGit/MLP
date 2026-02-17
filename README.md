# IMDB Sentiment Classification using MLP (NumPy)

This project implements a Multi-Layer Perceptron (MLP) from scratch using NumPy to classify IMDB movie reviews as positive or negative.

---

##  Project Overview

The goal of this assignment was to:

- Build a neural network without using deep learning frameworks
- Implement forward and backward propagation manually
- Train using Mini-batch Gradient Descent
- Evaluate performance using validation and test sets

The model uses only two sentence-level sentiment features:
- VADER compound polarity score
- TextBlob polarity score

## Model Architecture

- Input layer: 2 features (VADER + TextBlob)
- Hidden layer: 16 neurons with ReLU activation
- Output layer: 1 neuron with Sigmoid activation
- Loss function: Binary Cross-Entropy (BCE)
- Optimizer: Mini-batch Gradient Descent


## Results

- Validation Accuracy: ~77%
- Test Accuracy: ~77%

The model demonstrates stable convergence and balanced performance across both classes.



## Dataset

The dataset is not included in this repository due to file size limitations.

 Download the IMDB Dataset from Kaggle:
https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews


