# Feature Extraction and Classification Using Pre-trained Neural Networks

## Overview

This repository contains code and documentation for a project that leverages pre-trained neural networks for feature extraction and classification tasks. Specifically, it uses ResNet-18 as a fixed feature extractor to generate features for classification tasks. The project also includes optimizations for Support Vector Machine (SVM) and Random Forest classifiers, evaluating their performance on the test data.

## Dataset

The dataset used for this project consists of images categorized into two classes: Ants and Bees. For this project, the dataset was provided through the [PyTorch tutorial](https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html).

## Objectives

1. **Feature Extraction**:
   - Utilize a pre-trained ResNet-18 model from PyTorch as a fixed feature extractor.
   - Extract features for training images, producing an Nx512 dimensional array.

2. **Model Training and Evaluation**:
   - Train and optimize Support Vector Machine (SVM) and Random Forest classifiers.
   - Evaluate model performance using accuracy and F1 score on the test data.

