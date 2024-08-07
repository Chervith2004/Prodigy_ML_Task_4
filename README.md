# Prodigy_ML_Task_4

Linkedin Post link: https://www.linkedin.com/posts/gottipati-2004-chervith_machinelearning-prodigyinfotech-activity-7213157775147683840-d0Lt?utm_source=share&utm_medium=member_desktop

Gesture Recognition Using CNN: This repository contains the code and resources for a gesture recognition project using Convolutional Neural Networks (CNN). The project involves preprocessing image data, building a CNN model, and training the model to classify different hand gestures. The dataset used for this project is the LeapGestRecog dataset.

Table of Contents: 
-Project Overview 
-Data Preprocessing 
-Model Architecture 
-Training the Model 
-Evaluation
-Results 

1.Project Overview: The goal of this project is to build a CNN model to recognize hand gestures from grayscale images. The dataset consists of images of 10 different hand gestures. The model is trained to classify these gestures with high accuracy.

2.Data Preprocessing: The data preprocessing steps include: Loading the Data: Reading images from the dataset directory. Label Encoding: Creating a dictionary to map gesture names to numerical labels. Resizing Images: Resizing all images to a fixed size of 150x150 pixels. Normalization: Scaling pixel values to the range [0, 1]. One-Hot Encoding: Converting class labels to one-hot encoded vectors.

3.Model Architecture: The CNN model is built using Keras. The architecture consists of: 4 convolutional layers with ReLU activation and max-pooling A flattening layer 2 fully connected dense layers with ReLU activation An output layer with softmax activation for classification

4.Training the Model: The model is compiled with the Adam optimizer and categorical cross-entropy loss. Training involves fitting the model to the training data and validating on the test data. Early stopping, model checkpointing, and learning rate reduction are used to optimize the training process.

5.Evaluation: The trained model is evaluated on the test data to determine its accuracy and loss.

6.Results: The model achieves high accuracy on both the training and test datasets. The final test accuracy is approximately 99.90%.

