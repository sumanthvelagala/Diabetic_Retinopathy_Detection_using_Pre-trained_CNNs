# Diabetic Retinopathy Detection with Pre-trained CNNs using Transfer Learning

This repository contains a deep learning project focused on classifying diabetic retinopathy using a minimal dataset and transfer learning. The study evaluates and compares the performance of six widely used pre-trained convolutional neural network (CNN) models.


# Project Timeline

**Completed:** May 2024  
**Published Paper:** *Indian Journal of Science and Technology*


# Paper Reference

**Title:** *Evaluating Performance of Pre-trained Models for Diabetic Retinopathy Detection with a Minimal Dataset using Transfer Learning*  
**Author:** Sumanth Velagala  
**Journal:** Indian Journal of Science and Technology  


# Project Objective

The goal of this project is to assess how effectively pre-trained deep learning models can classify retinal fundus images into two categories: `dr` (diabetic retinopathy) and `nodr` (no diabetic retinopathy). The models are trained using a very limited number of images and evaluated based on their training accuracy, validation accuracy, and final test performance.


# Models Evaluated

The following pre-trained CNN models were used:

- DenseNet201  
- ResNet152  
- VGG16  
- InceptionV3  
- MobileNet  
- EfficientNetB0

All models were loaded with ImageNet weights and fine-tuned with frozen base layers and a custom classification head.


# Dataset Structure

── Dataset/
  ├── train/
  │ ├── dr/
  │ └── nodr/
  ├── valid/
  │ ├── dr/
  │ └── nodr/
  └── test/
  ├── dr/
  └── nodr/

