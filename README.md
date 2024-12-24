# Generating Paintings from Photos

This repository contains a Generative Adversarial Network (GAN) implementation that transforms real photos into Monet-style paintings. The model consists of a generator and a discriminator, trained using a dataset of photographs and Monet paintings.

## Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Dataset](#dataset)
- [Training](#training)
- [Visualization](#visualization)

## Features

- **Generator**: A convolutional neural network that generates Monet-style images from real photos.
- **Discriminator**: A neural network that distinguishes between real Monet paintings and generated images.
- **Training Loop**: Implements the training process for both the generator and discriminator.
- **Visualization**: Visualizes the generated images alongside the real photos.

## Requirements

To run this code, you will need:

- Python 3.x
- PyTorch
- torchvision
- PIL (Pillow)
- Matplotlib

## Dataset
The dataset was taken from: https://www.kaggle.com/competitions/gan-getting-started/data

## Training
The training process consists of the following steps:

- Load the datasets and apply transformations.
- Initialize the generator and discriminator models.
- Define loss functions and optimizers.
- Train the models for a specified number of epochs.
The training loop alternates between updating the generator and the discriminator, printing the loss values at regular intervals.

## Visualization
After training, the model can visualize the generated Monet-style images. The 'visualize_predictions' function displays a set of real photos alongside their corresponding generated images.
