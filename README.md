# Land Use MLP Classification

## Overview  
This notebook performs image classification on the UCMerced Land Use dataset using Multi-Layer Perceptron (MLP) models. It demonstrates loading image data from Google Drive, optimizing MLP hyperparameters with Bayesian optimization, and evaluating different activation functions using accuracy and ROC curves.

## Features  
- Load and preprocess UCMerced Land Use image data from directory structure  
- Train MLP models with one hidden layer using convolutional inputs  
- Perform Bayesian optimization for hyperparameters (neurons, learning rate)  
- Compare three activation functions: ReLU, sigmoid, and tanh  
- Evaluate models with accuracy metrics and ROC/AUC curves  
- Visualize training loss and accuracy curves  

## Tech Stack  
- Python  
- Jupyter Notebook / Google Colab  
- TensorFlow and Keras for deep learning  
- Matplotlib for visualization  
- Scikit-learn for metrics and evaluation  
- bayesian-optimization package for hyperparameter tuning  
- numpy and os for data handling  

## How to Use  
1. Upload UCMerced Land Use dataset to Google Drive in the specified directory structure.  
2. Open the notebook in Google Colab or Jupyter.  
3. Mount Google Drive when prompted.  
4. Install required libraries using pip commands included in the notebook.  
5. Run the notebook cells sequentially to load data, train models, and visualize results.  

## Status  
This notebook is cleaned up and organized for clear presentation and reproducibility on GitHub.