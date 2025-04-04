# ResNet-CNN---Flower-Image-Classification-

# Flower Classification using Deep Learning

This project focuses on distinguishing between "roses" and "daisies" using deep learning techniques for image classification tasks.

## Introduction

In this project, we explore various preprocessing techniques, including morphological transformations, and delve into data augmentation using data generators to enhance the diversity of our training dataset. We'll build and analyze different network architectures through ablation experiments, perform hyperparameter tuning for optimal model performance, and implement a mechanism to store the best model on disk.

The dataset used in this project is a flowers dataset specially designed to familiarize ourselves with essential deep learning principles. Our journey aims to equip us with practical knowledge and skills that can be applied to more complex image classification tasks.


Project Structure
The project is organized as follows:

flowers/: Contains the dataset with subdirectories for each class (daisy and rose).
models/: Stores the best model weights obtained during training.
resnet-architecture-CNN-Image-Classification.ipynb: Jupyter notebook containing the code for the project.

## Data Augmentation
We implement data augmentation techniques using custom data generators to improve the model's generalization.

## Network Architecture
We use ResNet-18 as the base network architecture for flower classification.

## Hyperparameter Tuning
We perform hyperparameter tuning, including learning rate decay and optimization algorithms, to improve the model's performance.

## Results
The final model achieves an accuracy of 85% on the validation set and has been saved for future use.

Conclusion
This project demonstrates how to build a deep learning pipeline for flower classification. It covers data preprocessing, data augmentation, model training, hyperparameter tuning, and result analysis.

Feel free to explore the notebook and experiment with different techniques to further enhance the model's performance.
