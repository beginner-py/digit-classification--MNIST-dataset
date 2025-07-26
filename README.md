# Image Classification using Neural Networks (Keras + OpenCV)

This project demonstrates a simple Neural Network (NN) for image classification using a publicly available dataset from Keras.
The project is designed for beginners to understand the basic workflow of deep learning—right from data preprocessing using OpenCV to building and training a neural network with Keras and making predictions.

├── dataset/                  # Downloaded Keras dataset (e.g., MNIST)
├── preprocessing/            # Image preprocessing scripts using OpenCV
├── model/                    # Neural Network model definition and training code
├── prediction_system.py      # Script to classify new images
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies

# Overview

Preprocessing: Basic image preprocessing is performed using OpenCV for tasks like resizing, normalization, grayscale conversion, etc.

Model: A simple Neural Network is built using Keras Sequential API.

Training: The model is trained for 10 epochs to learn image classification.

Prediction System: A Python script is included to classify any new image using the trained model.

