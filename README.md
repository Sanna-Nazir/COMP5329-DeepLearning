# COMP5329-DeepLearning
University of Sydney Coursework for COMP5329: Deep Learning (Semester 1, 2020)

The assignments were completed as part of the COMP5329 unit of The University of Sydney by [Sanna Nazir](https://github.com/Sanna-Nazir), [Anshu Kumar](https://github.com/anshukr5) and [Samarth Sehgal](https://github.com/samarthsehgal97). There were two assignments undertaken. Details of each assignment are as follows:

1. [Assignment 1](https://github.com/Sanna-Nazir/COMP5329-DeepLearning/tree/main/Assignment_1)

The aim of the project is to build a multilayer neural network from scratch to accomplish a multi-class classification task on the provided dataset **without using any Deep Learning frameworks (Tensorflow, Caffe or Keras)**. The model built had various modules attached to it, namely:

    1. use of more than one hidden layer
    2. ReLu activation
    3. Weight decay
    4. Momentum in SGD
    5. Dropout
    6. Softmax and cross-entropy loss
    7. Mini-batch training
    8. Batch Normalization
  
  
2. [Assignment 2](https://github.com/Sanna-Nazir/COMP5329-DeepLearning/tree/main/Assignment_2)

The goal of this assignment was to implement an image classifier that predicts the labels of image data sample. Each sample of the provided dataset included:

  1. an image
  2. one or more (up to 20) labels
  3. a short caption that summarizes the image

For this assignment, We have employed the technique of transfer learning using the ResNet50 network, the ResNext network as well as the VGG19 network (on tensorflow) to create the base of our custom neural network. On top of the existing base model, we have enabled layers to train the model on our custom dataset. Following the network creation, we have enabled the output layer with 20 neurons (for 20 classes), sigmoid activation function coupled with BinaryCrossEntropy Loss or BCEWithLogitsLoss so that the network is able to handle multi-label classification.
