# Traffic Sign Classification with Deep Learning

## Overview

This project focuses on the development of a traffic sign classification system using deep learning techniques. The goal is to create a model capable of accurately identifying and classifying traffic signs based on images. The system is built using the Python programming language, the TensorFlow and Keras libraries for deep learning, and the Tkinter library for creating a simple graphical user interface.

## Key Features

- **Model Architecture:** The core of the project is a Convolutional Neural Network (CNN) built with Keras. The model is trained on a dataset containing images of various traffic signs, and it learns to classify them into different categories.

- **Graphical User Interface (GUI):** The project includes a user-friendly GUI implemented with Tkinter. Users can upload an image of a traffic sign, and the system will provide a real-time classification result.

- **Pre-trained Model:** A pre-trained deep learning model is provided, allowing users to quickly test the classification system without going through the training process.

## Dataset

The model is trained on a dataset of traffic sign images, with each class representing a different type of traffic sign. The dataset used for training is not included in this repository due to its size. You can use publicly available datasets such as the German Traffic Sign Recognition Benchmark (GTSRB) dataset for training.

## Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/traffic-sign-classification.git
   cd traffic-sign-classification

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   
2. **Run the application:**
   ```bash
   python traffic_sign_classifier.py
   
3. **Upload an image through the GUI to see the classification result.**

