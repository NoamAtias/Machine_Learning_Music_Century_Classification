# Homework 1: Music Century Prediction

This Homework focuses on building models to predict the century in which a piece of music was released. We will be using the "YearPredictionMSD" dataset from the Million Song Dataset.
### This Homework was done together with Chanel Michaeli.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Assignment Outline](#assignment-outline)
  - [Data Description](#data-description)
  - [Model Building](#model-building)
  - [Training Procedure](#training-procedure)
  - [Evaluation](#evaluation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

In this assignment, our objective is to develop models that can predict the century in which a piece of music was released. By leveraging deep learning techniques, we aim to capture underlying patterns and trends in the music data to enable accurate predictions. The goal is to understand the training procedure and implement it without relying on additional packages, especially not PyTorch.

## Dataset

The dataset for this assignment is the "YearPredictionMSD" dataset, which is based on the Million Song Dataset. You can download the dataset from the UCI Machine Learning Repository using the following link: [YearPredictionMSD Dataset](https://archive.ics.uci.edu/ml/datasets/yearpredictionmsd). Additional information about the dataset and its context can be found on the [Million Song Dataset website](http://millionsongdataset.com/pages/tasks-demos/#yearrecognition).

## Assignment Outline

### Data Description

The "YearPredictionMSD" dataset contains audio features extracted from a large collection of music recordings. Each data instance represents a song and includes various features, such as timbre statistics, spectral features, and more. The target variable is the release year of the song, which we will use to predict the century.

### Model Building

In this assignment, we will build our models without relying on additional packages like PyTorch. The objective is to understand the inner workings of the training procedure and implement it from scratch. We will explore different model architectures, such as fully connected neural networks, and experiment with various hyperparameters to optimize the model's performance.

### Training Procedure

We will implement the training procedure manually, without utilizing PyTorch's autograd engine. This includes initializing the model parameters, defining the loss function, performing forward and backward propagation, and updating the model's weights using gradient descent or other optimization algorithms.

### Evaluation

To evaluate the performance of our models, we will utilize appropriate metrics, such as mean squared error (MSE) or accuracy. We will measure the model's ability to predict the correct century for a given music piece and assess its overall performance.

## Usage

To replicate the results of this assignment, follow these steps:

1. Download the "YearPredictionMSD" dataset from the provided link.
2. Preprocess the data, including data cleaning, feature engineering, and splitting into training and test sets.
3. Implement the model architecture and training procedure.
4. Train the model using the training set and adjust hyperparameters as needed.
5. Evaluate the model's performance on the test set using appropriate metrics.
6. Document and analyze the results, including any insights or observations.

## Contributing

Contributions to this assignment are welcome. If you have any suggestions, improvements, or bug fixes, please submit a pull request or open an issue.
