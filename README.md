# Waste Classification System

This repository contains a Waste Classification System developed using the RealWaste dataset. The system employs deep learning techniques to classify real-world waste into predefined categories, supporting improved waste management and recycling efforts.

## Features
- **RealWaste Dataset**: Trained on a publicly available dataset featuring real-world waste images.
- **Deep Learning Model**: Uses a VGG16-based Convolutional Neural Network (CNN) for accurate classification.
- **End-to-End Pipeline**: Includes preprocessing, training, evaluation, and prediction workflows.
- **Visualization Tools**: Supports result analysis with confusion matrices and accuracy plots.

## Dataset
The system uses the [RealWaste dataset](https://archive.ics.uci.edu/dataset/908/realwaste), which includes images of waste items categorized into multiple classes. The dataset contains the following categories with their respective number of images:

- **Cardboard**: 461 files
- **Food Organics**: 411 files
- **Glass**: 420 files
- **Metal**: 790 files
- **Miscellaneous Trash**: 495 files
- **Paper**: 500 files
- **Plastic**: 921 files
- **Textile Trash**: 318 files
- **Vegetation**: 436 files

The dataset is split into training, validation, and test sets to ensure robust model performance. Preprocessing steps include resizing, normalization, and data augmentation to prepare the images for training.

