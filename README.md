# Dog_vision_model
Computer vision model to detect dog breeds based on an image. This model was created by using TensorFlow, Scikit-learn, Pandas, NumPy, and Matplotlib.

**Note** This notebook was generated in a Windows 10 WSL2 (Ubuntu) VM PowerShell terminal using miniconda, and it was optimized to use a GPU with a max memory usage of 6 GB. You can adjust the max GPU usage if you have more available GPU memory.

# 🐕 End-to-end Multi-class Dog Breed Classification

This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub

## 1. Problem

Identifying the breed of a dog given an image of a dog.

Example scenario... When I'm sitting at a cafe and I take a photo of a dog, I want to know what breed of dog it is.

## 2. Data

The data this notebook uses is from Kaggle's dog breed identification competition:

https://www.kaggle.com/c/dog-breed-identification/data

## 3. Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image.

https://www.kaggle.com/competitions/dog-breed-identification/overview/evaluation

## 4. Features

Some information about the data:
* This notebook deals with images (unstructured data) so it's probably best to use deep learning/transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set. (These images have labels)
* There are around 10,000+ images in the test set. (These images have no labels, because we will want to predict them).

# How to set up environment:

1. create a conda environment using the `environment.yml` and/ or `requirments.txt` file. *(list of installed packages will be added below)*
2. create a `data` folder and download the data files from Kaggle to this folder
3. use `conda activate ./env` in the directory location.
4. start a `jupyter notebook` and open the dog vision notebook. 

**Note:** Setup may be different depending on your terminal, IDE and/or OS.

### If you have issues using either the `environment.yml` or the `requirements.txt`, here is how I installed the packages when I created the environment:
  
  First:
  
  `conda create --prefix ./env jupyter pandas numpy scikit-learn matplotlib pip`

  Then:

  `conda activate ./env`
  
  `pip install tensorflow[and-cuda]` (GPU) or `pip install tensorflow` (CPU) 
  
  `pip install tensorflow-hub`
