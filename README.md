
# AI Driven Medical Diagnosis of Pneumonia
![image](https://github.com/AmruhaAhmed/Code-Clause-Internship-AI-Driven-Medical-Diagnosis-/assets/98407069/33240b86-ef4f-4077-90d1-924622b2fe2d)

## Overview

This repository contains code and models developed during my tenure as an Artificial Intelligence Intern at Code Clause from May 2024 to June 2024 . The primary objective of this project is to detect the presence or absence of pneumonia using chest X-ray images sourced from the PneumoniaMNIST dataset, which is a part of the larger MedMNIST dataset collection. Pneumonia is a serious condition that causes inflammation in one or both lungs, and early detection is crucial for effective treatment.


## Project Structure
Below are the key steps involved:

1. Installation
2. Dataset
3. Visualization
4. Data Preprocessing
5. Model Architecture
6. Model Evaluation
7. User Interface

## Installation

To run this project, you need to install the required libraries. The following libraries are necessary for this project:

1. Gradio
2. TensorFlow
3. Matplotlib
4. MedMNIST

## Dataset

The dataset used in this project is the PneumoniaMNIST dataset from MedMNIST, which consists of chest X-ray images. Each image is of 224x224 pixels, in grayscale. The dataset is divided into training, validation, and testing sets. 

Size of Training Set = 4708 

Size of Test Set = 624

Size of Validation Set= 524


## Visualization

Two images have been visualized from the training set using Matplotlib
![image](https://github.com/user-attachments/assets/c04ba424-4e4e-425f-b633-897e6fae41cc)


## Data Preprocessing

The images are converted from grayscale to RGB format and their dimensions are expanded to match the input shape required by the ResNet50 model.

## Model Architecture

The concept of transfer learning is utilized .The model is built using the ResNet50 architecture as the base model, with additional layers added for the specific task of pneumonia detection.

## Model Evaluation

The following metrics were utilized to analyze the performance of the model:
1. Accuracy = 0.9038461538461539
2. Precision =  0.9155590503246753
3. Recall = 0.9038461538461539
4. F1 Score = 0.9003725478782234
5. Confusion Matrix
   
   ![image](https://github.com/user-attachments/assets/754e197f-a210-43b6-98da-ad7ba719616a)

## User Interface

The project utilizes the Gradio library to create an interactive web interface for the AI-driven medical diagnosis system. Gradio is a powerful library that allows developers to quickly deploy machine learning models and create user-friendly interfaces without extensive front-end development knowledge.
![image](https://github.com/user-attachments/assets/8d90ced4-9896-4170-88a5-57583951b149)



**Do Star this repository if you find it useful!**



