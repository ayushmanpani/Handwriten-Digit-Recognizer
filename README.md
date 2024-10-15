# Handwritten Digit Recognizer

This repository contains implementations of a Handwritten Digit Recognizer using various approaches in Jupyter Notebook format. The goal of this project is to build models that can accurately recognize handwritten digits from the MNIST dataset.

## Table of Contents
- [Project Overview](#project-overview)
- [Files Included](#files-included)
- [Setup and Requirements](#setup-and-requirements)

## Project Overview

The project consists of three different implementations of a Handwritten Digit Recognizer:

1. **Handwritten Digit Recognizer with Libraries**: 
   - A convulated neural network-based model utilizing Tensorflow.
   
2. **Handwritten Digit Recognizer Without Libraries**:
   - An implementation of the recognizer from scratch without using any libraries, complete with a graphical user interface (GUI).
   
3. **Handwritten Digit Recognizer Using Momentum Algorithm**:
   - An advanced version of the recognizer that incorporates the momentum algorithm to optimize the learning process. Also from scratch without using any libraries.

## Files Included

### Jupyter Notebooks
- **`Digit REcognizer with CNN.ipynb`**: Implementation using convulated neural networks(CNN) with libraries.
- **`Handwritten Digit recog with GUI.ipynb`**: Implementation without libraries with GUI.
- **`digit classification-momnetum algo.ipynb`**: Implementation using the momentum optimization algorithm.

### Data Sets(All datasets have been taken from Kaggle)
- **`train.csv.zip`**: Contains training images and labels for the digit recognizer.
- **`test.csv.zip`**: Contains testing images for evaluating the models.
- **`mnist_original.mat.zip`**: Dataset for **`Handwritten Digit recog with GUI.ipynb`** file

## Setup and Requirements

To run the Jupyter notebooks, you will need the following libraries installed:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scipy
- Tensorflow ( for Digit REcognizer with CNN) 
- Any other libraries required by the specific implementations

You can install the necessary libraries using pip:

```bash
pip install numpy matplotlib tensorflow pandas scipy
