# AI-Driven TB Detection System

This project implements an AI-driven system that uses a Convolutional Neural Network (CNN) to detect tuberculosis (TB) from chest X-ray images. It leverages the Shenzhen dataset to train and evaluate the model, making it a promising tool for rapid TB screening in areas with limited access to radiologists.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Architecture](#model-architecture)
- [Training & Evaluation](#training--evaluation)
- [Future Enhancements](#future-enhancements)

## Overview

The AI-Driven TB Detection System is designed to provide:
- **Rapid and Accurate Screening**: Detects TB with high accuracy through state-of-the-art convolutional neural networks.
- **Non-Invasive Diagnosis**: Uses chest X-ray images which are non-invasive and widely available.
- **Support for Resource-Limited Settings**: Provides an effective diagnostic tool where access to expert radiologists may be limited.

## Dataset

This project uses the **Shenzhen dataset**, which includes chest X-ray images along with corresponding metadata. The dataset is structured as follows:
- **Images Folder**: Contains chest X-ray images.
- **Metadata CSV**: A CSV file (`shenzhen_metadata.csv`) that holds the exam details including patient findings. The `findings` column is processed to create binary labels (0 for Normal, 1 for TB).

## Features

- **Deep Learning-Powered**: Leverages CNN to detect TB patterns.
- **Fast Processing**: Capable of real-time image processing and prediction.
- **User-Friendly Interface**: Includes clear preprocessing and model evaluation code.
- **Modular Design**: Easy to customize, extend, and integrate with other applications.
- **Visualization**: Provides training graphs to monitor model performance over epochs.

## Requirements

- Python 3.7 or above
- TensorFlow 2.x
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/tb_detection.git
   cd tb_detection
