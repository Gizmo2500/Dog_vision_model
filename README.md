# Dog_vision_model
Computer vision model to detect dog breeds based on an image. This model was created by using TensorFlow, Scikit-learn, Pandas, NumPy, and Matplotlib

# 🐕 End-to-end Multi-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub

## 1. Problem

Identifying the breed of a dog given an image of a dog.

Example scenario... When I'm sitting at a cafe and I take a photo of a dog, I want to know what breed of dog it is.

## 2. Data

The data this notebook uses is from Kaggle's dog breed identification competition:
https://www.kaggle.com/c/dog-breed-identification/overview

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

## 4. Features

Some information about the data:
* We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set. (These images have labels)
* There are around 10,000+ images in the test set. (These images have no labels, because we will want to predict them).
