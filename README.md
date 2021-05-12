# Simple-Image-Classifier
## Introduction
This repo contains the Colab Notebook for building a Simple Image Classifier using Convolutional Neural Networks(CNN)
The project has four parts:
## Part 1: Building a CNN model using MNIST dataset
- Loading MNIST dataset
- Displaying number of samples
- Plotting example digits
- Dataset pre-processing
- Building CNN model, training and saving model
- Model Evaluation: loss charts
## Part 2: Testing the model using handwritten digits
- Loading saved model
- Take 30 pics of handwritten digits
- Classify the digits using the loaded model
## Part 3: Transfer of learning
- Importing pre-trained VGG16 model, without 'head' layer
- Extracting the last layer from the 3rd block of the model
- Adding classification layers
- Training the model
- Comparing metrics of new model vs the original model
## Part 4: Visualizing Filter Maximizations, Gradient-weighted Class Activation Mapping (GRAD-CAM)
- Generating GRAD-CAM heat map
- Overlaying heatmap onto test image to see which areas were most important in achieving class prediction
- Maximizing filter activations and visualizing them
