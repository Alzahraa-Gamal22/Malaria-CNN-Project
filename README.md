# Malaria Detection Project 

# Malaria Detection using Convolutional Neural Networks
#### This project implements a Deep Learning model to classify cell images into two categories: Parasitized and Uninfected. The goal is to provide an automated and reliable method for malaria diagnosis using blood smear images.

### Project Overview
The model is built using TensorFlow and Keras, leveraging a Sequential CNN architecture. It processes images of size 128x128 pixels to detect patterns associated with malaria infection.

### Model Architecture
The network consists of several layers designed to extract features and classify the images accurately:



Convolutional Layers: Four Conv2D layers with increasing filters (32, 64, 128, 256) using ReLU activation.

Normalization: BatchNormalization is applied after each convolutional layer to stabilize training and improve convergence.

Pooling: MaxPooling2D layers are used to reduce spatial dimensions and computational load.

Fully Connected Layers: Two Dense layers (256 and 128 neurons) with ReLU activation.

Regularization: Dropout layers (0.5 and 0.3) are integrated to prevent overfitting and improve generalization.

Output Layer: A single neuron with Sigmoid activation for binary classification.

Overfitting Mitigation
To ensure the model performs well on unseen data, the following strategies were implemented:

Dropout: Randomly deactivating neurons during training to reduce dependency on specific paths.

Batch Normalization: Helping the model generalize better by normalizing the inputs to each layer.

Validation Split: 20% of the data was reserved for validation to monitor performance and detect overfitting early.

### Requirements and Setup
To run this project, the following libraries are required:

TensorFlow

NumPy

Matplotlib

Kagglehub (for dataset download)

### Training Configuration
Optimizer: Adam.

Loss Function: Binary Crossentropy.

Metrics: Accuracy.

Batch Size: 16 for training, 1 for testing.ia_Project.ipynb.


### Dataset
The dataset used contains thousands of cell images. Due to its size, it is not included in this repository. You can find the dataset [https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria/data]


