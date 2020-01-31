# Hand written digit classifier model with tensorflow 

## Import dependencies

We start by importing TensorFlow and other supporting libraries that are used for data processing and visualization.

## Download and explore the MNIST dataset

The MNIST database contains 60,000 training images and 10,000 testing images of handwritten digits. We will use the dataset to train our digit classification model.
Each image in the MNIST dataset is a 28x28 grayscale image containing a digit from 0 to 9, and a label identifying which digit is in the image.

![Hand Written Digit](https://miro.medium.com/max/372/1*AO2rIhzRYzFVQlFLx9DM9A.png)

## Train a TensorFlow model to classify digit images

Next, we use Keras API to build a TensorFlow model and train it on the MNIST "train" dataset. After training, our model will be able to classify the digit images.

Our model takes a 28px x 28px grayscale image as an input, and outputs a float array of length 10 representing the probability of the image being a digit from 0 to 9.

Here we use a simple convolutional neural network, which is a common technique in computer vision.

## Evaluate our model

We run our digit classification model against our "test" dataset that the model has not seen during its training process to confirm that the model did not just remember the digits it saw but also generalize well to new images.
