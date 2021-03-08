# :label: Convolutional-Neural-Network-CNN-

This Demonstrates training a simple Convolutional Neural Network (CNN) to classify CIFAR images.This training and creating of model uses Keras.

The CIFAR10 dataset contains 60,000 color images in 10 classes, with 6,000 images in each class. The dataset is divided into 50,000 training images and 10,000 testing images. The classes are mutually exclusive and there is no overlap between them.

As input, a CNN takes tensors of space (image_height, image_width, color_channels), ignoring the batch size. If you are new to these dimensions, color_channels refers to (R,G,B). In this example, we will configure our CNN to process inputs of shape(32, 32, 3), which is the format of CIFAR images. You can do this by passing the argument input_shape to our first layer.
