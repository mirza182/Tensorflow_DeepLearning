# Deep Learning Projects with Tensorflow
Welcome to my Deep Learning repository! Here, I share my journey through various deep learning projects using TensorFlow. Each project is implemented in a separate Jupyter notebook, showcasing different aspects of deep learning.

Welcome to my Fashion-MNIST deep learning project! In this repository, I explore the fascinating world of fashion using neural networks. Let’s dive into the details:

# Overview
Fashion-MNIST is a dataset of grayscale images representing various fashion items.
It serves as an alternative to the classic MNIST dataset, providing a more challenging task for image classification.
Here are the key points about Fashion-MNIST:

# Key Details

# Dataset Composition:
The dataset consists of 70,000 examples in total.
The training set contains 60,000 images, and the test set contains 10,000 images.
Each example is a 28x28 pixel grayscale image associated with a label from 10 classes.

# Classes:
The 10 classes represent different fashion items:
T-shirt/top
Trouser
Pullover
Dress
Coat
Sandal
Shirt
Sneaker
Bag
Ankle boot
# Achievements:
I successfully created a deep learning model which predicted which class a certain image belonged to.
In the hidden layer I used relu activation function and also L2 regularizator which helped me preventing the model in overfitting. In the output layer, as I had too many classes, I used softmax activation function that gave me a probability distribution which made it easy to identify which class a certain image belonged to.
The training and testing accuracies were closely intact and the predictions were mostly accurate with a testing accuracy of 90 percent without L2 regularizer and 85 percent with L2 regularizer
