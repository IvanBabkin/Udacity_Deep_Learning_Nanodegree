# Udacity Deep Learning Nanodegree
This repository contains 3 projects that were completed as part of Udacity's Deep Learning Nanodegree.

Find Nanodegree [here.](https://www.udacity.com/course/deep-learning-nanodegree--nd101)

## [Project 1 - Predicting Bike-Sharing Patterns](https://github.com/IvanBabkin/Udacity_Deep_Learning_Nanodegree/tree/main/Project%201%20-%20Predicting%20Bike-Sharing%20Patterns)
The goal of this project is to build a neural network with fully connected layers only utilising python's NumPy library. More specifically, this neural network is used to predict daily bike rental ridership patterns from hourly data. Features like temperature, humidity, weekday and etc., are used in order to determine the number of bike riders.

* Key techniques used:
  * Forward pass through the neural network
  * Backpropagation
  * Weights initialisation
  * Hyperparameter tuning


## [Project 2 - Landmark Classification and Tagging for Social Media](https://github.com/IvanBabkin/Udacity_Deep_Learning_Nanodegree/tree/main/Project%202%20-%20Landmark%20Classification%20and%20Tagging%20for%20Social%20Media)
The purpose of this project is to build CNNs models to automatically predict the location of the image based on any landmarks depicted in the image. Firstly, two different CNN models are built from scratch using PyTorch, experimenting with model architecture, weight initialisation and other hyperparameters. Secondly, VGG16 and ResNet50 models' architectures are adjusted to suit while their pre-trained weights are similarly used to make more accurate predictions on the dataset. The performance of the models is compared and contrasted, and ultimately, the best model is chosen to classify images based on the visible landmarks. 

* Key techniques used:
  * Creating and training CNN models with PyTorch
  * Improving CNN performance through optimizer and model hyperparameters tuning
  * Transfer Learning

## [Project 3 - Generate TV Scripts](https://github.com/IvanBabkin/Udacity_Deep_Learning_Nanodegree/tree/main/Project%203%20-%20Generate%20TV%20Scripts)
The objective of this project is to create an RNN that can generate new, "fake" TV scripts based on patterns it recognizes in the training data, which consists of Seinfeld scripts from 9 seasons. More specifically, the goal is to build a suitable neural network architecture, taking into how text data should be processed and prepared for input into the RNN as well as word embedding.  Ultimately, this project is in the field of Natural Language Processing. 

* Key techniques used:
  * Batching data (considering the batch size and word sequence length)
  * Creating and training RNN models with PyTorch
  * Improving RNN performance through data, model and training parameters tuning
  * Word embedding
  * LSTM/GRU layers
