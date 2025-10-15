# AlexNet-Binary-Classification
In this project we are trying to implemet Alexnet architectere and fit our dataset for the binary classification a base model and a modified model of alexnet is trained.
# Binary Image Classification using AlexNet

## Overview
This project implements a binary classification system for image data using AlexNet and improved AlexNet architectures. The code is designed as an educational template for deep learning projects.

## Features
- Custom dataset loading and preprocessing
- Data augmentation techniques
- AlexNet implementation from scratch
- Transfer learning with pre-trained models
- Comprehensive evaluation metrics
- Visualization tools
- Modular and reusable code structure

## Dataset Structure
Organize your dataset in the following structure:
your_dataset_folder/
├── class_0/ # Images for class 0
└── class_1/ # Images for class 1



## Quick Start
1. **Setup Dataset**: Organize your images into `class_0` and `class_1` folders
2. **Update Paths**: Modify `dataset_path` and `classes` in the notebook
3. **Run in Colab**: Execute cells sequentially in Google Colab
4. **Monitor Training**: Observe training progress and results

## Requirements
```bash
torch>=1.8.0
torchvision>=0.9.0
scikit-learn>=0.24.0
matplotlib>=3.3.0
seaborn>=0.11.0
pandas>=1.2.0
numpy>=1.19.0
Pillow>=8.0.0
tqdm>=4.50.0


Model Architectures
Standard AlexNet: Original architecture implementation


Improved AlexNet: Enhanced version with custom modifications

Transfer Learning: Using pre-trained weights

Code Structure
Binary_Classification_Alexnet.ipynb - Main notebook

Dataset loading and splitting functions

Custom dataset class

Data augmentation pipelines

Model training and evaluation

Visualization utilities
