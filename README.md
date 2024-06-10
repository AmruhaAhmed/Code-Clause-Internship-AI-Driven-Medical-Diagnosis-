
# AI Driven Medical Diagnosis of Pneumonia
![image](https://github.com/AmruhaAhmed/Code-Clause-Internship-AI-Driven-Medical-Diagnosis-/assets/98407069/33240b86-ef4f-4077-90d1-924622b2fe2d)



## Overview

This repository contains code and models developed during my tenure as an Artificial Intelligence Intern at Code Clause from May 2024 to June 2024 . The primary objective of this project is to detect the presence or absence of pneumonia using chest X-ray images sourced from the Med MNIST dataset. Pneumonia is a serious condition that causes inflammation in one or both lungs, and early detection is crucial for effective treatment.


## Project Structure
Below are the key steps involved:

1. Data Loading
2. Splitting of Data
3. Data Cleaning
4. Data Visualization
5. Defining Functions for Model Creation
6. Model Building
7. Model Evaluation
8. Prediction Using the Best Model
9. Model Deployment


Each image is in grayscale and of size 28 x 28 pixels.

## Models Implemented

I have implemented a variety of models, both simple neural networks and convolutional neural networks and stored them in different functions, to determine the best-performing architecture. Here is a summary of the models created:

### Functions for Simple Neural Networks Models

1. two_layers_softmax: Input and output layers, softmax activation.

2. two_layers_sigmoid: Input and output layers, sigmoid activation.

3. three_layers_softmax: Input, hidden, and output layers, softmax activation.

4. three_layers_sigmoid: Input, hidden, and output layers, sigmoid activation.

5. four_layer_softmax: Input, two hidden layers, output layer, softmax activation.

6. three_layer_softmax_SGD: Input, hidden, output layers, softmax activation, SGD optimizer.

7. four_layer_sigmoid: Input, two hidden layers, output layer, sigmoid activation.

### Functions for Simple Neural Networks Models

1. five_layer_cnn_softmax: Convolution, max pooling, input, hidden, output layers, softmax activation.

2. five_layer_cnn_sigmoid: Convolution, max pooling, input, hidden, output layers, sigmoid activation.

3. seven_layer_cnn_softmax: Two convolution, two max pooling, input, hidden, output layers, softmax activation.

4. seven_layer_cnn_sigmoid: Two convolution, two max pooling, input, hidden, output layers, sigmoid activation.

5. five_layer_cnn_softmax_avg_pooling: Convolution, average pooling, input, hidden, output layers, softmax activation.

6. seven_layer_cnn_softmax_avg_pooling: Two convolution, two average pooling, input, hidden, output layers, softmax activation.
## Model Performance
Among the 36 models created by varying epochs, Model 20 achieved the highest accuracy of 89.58%.


## Prediction

To facilitate predictions, the following functions were created:

1. image_preprocess: Resizes, converts to grayscale, and normalizes the image if the input is not of 28x28 pixels.

2. predict: Uses the preprocessed image, expands dimensions, and returns the predicted class.


## Model Deployment
Utilizing the Gradio library, I created a simple User Interface to deploy the model. 

Here is the final result:


https://github.com/AmruhaAhmed/Code-Clause-Internship-AI-Driven-Medical-Diagnosis-/assets/98407069/0f4dcdce-9e0b-48f1-860e-76e877f41c62



If you find this project helpful, please ⭐ this repository!

LinkedIn Post:  https://www.linkedin.com/posts/amruha-ahmed_codeclause-ai-artificialintelligence-activity-7196426442774138880-Txrn?utm_source=share&utm_medium=member_desktop
