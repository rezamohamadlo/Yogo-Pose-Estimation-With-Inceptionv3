# Yogo-Pose-Estimation-With-Inceptionv3
This is a project that has been done as an assignment for course "Convolutional Neural Networks With Tensorflow" for Coursera.org website.
This project implements a yoga pose classification model using the InceptionV3 architecture as a base, with transfer learning. The model is trained to classify images into five different yoga poses.

## Project Overview

In this project, we used the InceptionV3 model pre-trained on ImageNet as a feature extractor and added custom layers to classify images of yoga poses. The model was trained on a dataset of yoga poses, and a callback was implemented to stop training once the model achieved 99.9% accuracy.

## Dataset

The dataset used for training and validation is `yoga_poses`, which contains images of five different yoga poses:

- Chair
- Cobra
- Dog
- Tree
- Warrior

The dataset is divided into training and validation sets.

## Files

- `download_data.ipynb`: Script to download and extract the dataset.
- `preprocess_data.ipynb`: Script to set up data directories and preprocess images.
- `Yogo-Pose-Estimation-With-Inceptionv3.ipynb`: Contains the implementation of the pre-trained model with additional layers and the custom callback.
## Instructions

1. **Download and Extract Dataset**
   ```bash
   python download_data.py
