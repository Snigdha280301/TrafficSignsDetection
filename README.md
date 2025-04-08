# Traffic Sign Detection System

A real-time traffic sign recognition system built using **Convolutional Neural Networks (CNNs)** and **OpenCV**, capable of detecting and classifying 43 classes of traffic signs from live video feeds.

## Overview

This project aims to assist autonomous systems and driver assistance technologies by accurately identifying traffic signs in real time. The model is trained on a custom-labeled dataset with over **40,000 images**, achieving a **93% test accuracy**.

## Features

- Real-time traffic sign detection from webcam/video feed
- Trained CNN model using OpenCV and NumPy
- 93% test accuracy across 43 traffic sign classes
- Processes frames at ~25 FPS
- Data augmentation for improved generalization
- Train-test split to minimize overfitting

## Tech

- Python  
- OpenCV  
- NumPy  
- scikit-learn  
- Matplotlib (for visualization)

## Dataset

The dataset contains **40,000+ labeled images** from 43 categories of traffic signs, organized into folders by class index.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/traffic-sign-detection.git
   cd traffic-sign-detection

