# Malaria Detection Project 
## Malaria Detection using CNN 
This project focuses on building a Convolutional Neural Network (CNN) to automate the process of detecting malaria parasites in thin blood smear images.

### Project Overview
Goal: Classify cell images into two categories: Parasitized or Uninfected.

Model: Deep Learning model using CNN architecture.

Frameworks: Python, TensorFlow/Keras, and Pandas.

### Techniques to Improve Performance
Since this model aims for high accuracy in medical diagnosis, I implemented several techniques to handle common issues like Overfitting:

Data Augmentation: To increase the variety of training images.

Dropout Layers: To prevent the model from over-relying on specific neurons.

Early Stopping: To stop training when the validation loss stops improving.

### Dataset
The dataset used contains thousands of cell images. Due to its size, it is not included in this repository. You can find the dataset [https://www.kaggle.com/datasets/iarunava/cell-images-for-detecting-malaria/data].


Bash
pip install tensorflow pandas matplotlib scikit-learn
Run the Jupyter Notebook: Malaria_Project.ipynb.
