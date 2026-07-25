# Corruption Robustness and Calibration in Image Classification

## Overview

This project investigates the robustness and confidence calibration of deep learning image classification models under common image corruptions.

A ResNet18 model is trained on the CIFAR-10 dataset and evaluated using the CIFAR-10-C benchmark.

The project evaluates four corruption types:
- Gaussian Noise
- Motion Blur
- Fog
- JPEG Compression

The effects of corruption severity on classification accuracy and Expected Calibration Error (ECE) are analysed. Three mitigation techniques are also evaluated:

- Data Augmentation
- Test-Time Normalization
- Selective Prediction

## Dataset

- CIFAR-10
- CIFAR-10-C

Dataset Source:
https://github.com/hendrycks/robustness

## Framework

- Python
- PyTorch

## Authors

- Santosh Doddaiah
- Mohamed Meraj Mansur Sharif
- Manveer Singh

University of Europe for Applied Sciences

Potsdam, Germany
