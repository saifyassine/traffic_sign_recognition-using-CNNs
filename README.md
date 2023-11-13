# Traffic Signr Recognition Project using CNNs
This project focuses on build a Convolutional Neural Networks (CNNs) based model to recognize and classify German traffic signs using the GTSRB (German Traffic Sign Recognition Benchmark) dataset.

## Overview
Traffic sign recognition plays a crucial role in autonomous vehicles and driver assistance systems. This project aims to develop and implement a machine learning model capable of accurately identifying and classifying various traffic signs commonly found on German roads.

## Dataset
The project utilizes the GTSRB dataset, comprising approximately 40,000 25x25 RGB images of 43 different traffic signs. The dataset captures signs under various conditions, including different weather, lighting, and angles, simulating real-world scenarios.

#### Dataset Source: Kaggle - GTSRB Dataset: https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign?select=Train

## Project Workflow
### 1. Data Preprocessing
The dataset is preprocessed, converting the CSV files into .npy files for efficient data handling.
Data augmentation techniques are applied to increase dataset diversity.
### 2. Model Development
A CNN model is constructed to learn and classify traffic signs based on the processed data.
The model architecture consists of convolutional layers, pooling, dropout for regularization, and fully connected layers.
### 3. Model Training and Evaluation
The model is trained using a portion of the data and validated using a separate test set.
Training involves optimizing the model parameters to achieve high accuracy in sign classification.
### 4. Model Deployment
The trained model is saved for future use and is also converted into a TensorFlow Lite model for potential deployment in resource-constrained environments.
## Instructions for Use
### Prerequisites
#### Python3
#### The libraries in the requirement.txt file
### Steps
#### 1.Dataset Handling

Download the dataset from the provided Kaggle link and organize it in the specified directory structure.
Convert the provided CSV files to .npy files as per the provided example code.
#### 2.Model Training and Evaluation

Run the traffic_sign_recognition.py script to train the model.
Evaluate the model's performance using the test data and visualize the results.
#### 3.Model Deployment

Convert the model to a TensorFlow Lite model for deployment on resource-constrained platforms.
