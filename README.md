# Dog vs Cat Classification - Transfer Learning

This project aims to develop an image classifier using TensorFlow to distinguish between images of dogs and cats. The model is built using transfer learning on the Kaggle dataset using Google Colab, specifically the "Dogs vs Cats" dataset.

## Introduction
Image classification is a fundamental task in computer vision, and the ability to differentiate between images of dogs and cats is a common problem statement. This project utilizes the TensorFlow framework, leveraging transfer learning techniques to build a robust model capable of accurately classifying these animal images.

## Output
![op1](https://github.com/dineshrx/Dog-vs-Cat-Classification-Transfer-Learning/assets/144202549/45605507-0730-407e-a6f5-7d34f7be2b75)
![op2](https://github.com/dineshrx/Dog-vs-Cat-Classification-Transfer-Learning/assets/144202549/ab06112c-2a03-4a3e-a955-32c2340ca8d5)
## Setup
## Installation
Ensure the Kaggle library is installed to access the dataset:

!pip install kaggle

## Kaggle API Configuration
Configure the Kaggle API for dataset download:

!mkdir -p ~/.kaggle <br />
!cp kaggle.json ~/.kaggle/ <br />
!chmod 600 ~/.kaggle/kaggle.json

## Dataset

Download the 'Dogs vs Cats' dataset using the Kaggle API and extract the images for training the classifier: <br />
!kaggle competitions download -c dogs-vs-cats


## Preprocessing

Perform image preprocessing tasks such as resizing, labeling, and conversion to numpy arrays in preparation for modeling.

## Model Building

Split the dataset into training and testing sets, construct a neural network using transfer learning, train the model, and evaluate its performance.

## Predictions

Utilize the trained model to make predictions on new images and determine whether they are dogs or cats.

