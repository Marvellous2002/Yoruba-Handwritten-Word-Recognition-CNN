# Yoruba Handwritten Word Recognition Using CNN

## Overview

This was my undergraduate Computer Science project focused on developing an offline Yoruba handwritten word recognition system using a Convolutional Neural Network (CNN).

The project explored the application of deep learning and computer vision techniques to recognize handwritten Yoruba words from images.

## Objective

The objective was to develop a CNN-based system capable of recognizing handwritten Yoruba words and converting them into machine-readable text.

## Dataset

The project used handwritten Yoruba word samples collected from different individuals with different handwriting styles.

## Technologies and Tools

- Python
- PyTorch
- MLtu (Machine Learning Tools)
- Convolutional Neural Networks (CNN)
- CUDA/GPU acceleration
- ONNX
- Image preprocessing and augmentation

## Methodology

The project involved:

1. Dataset creation
2. Image preprocessing
3. Image resizing and normalization
4. Data augmentation
5. CNN model development
6. Model training
7. Model evaluation
8. Error analysis
9. Model inference

Data augmentation included random brightness adjustment, rotation, erode/dilate and sharpening.

## Model

The model used a CNN architecture with convolutional layers and a dense output layer.

Adam was used as the optimizer, while Connectionist Temporal Classification (CTC) loss was used for training.

GPU acceleration was used where available.

## Results

The model correctly recognized 19 out of 31 tested samples, giving a recognition accuracy of 61.29%.

The final reported Character Error Rate (CER) was 0.07407, while the Word Error Rate (WER) was 0.08445.

## Future Work

Possible improvements include:

- Expanding the Yoruba handwriting dataset
- Exploring transfer learning
- Increasing data augmentation
- Hyperparameter optimization
- Further error analysis
- Improving model generalization

## Project Documentation

The full undergraduate project report is available in this repository.
