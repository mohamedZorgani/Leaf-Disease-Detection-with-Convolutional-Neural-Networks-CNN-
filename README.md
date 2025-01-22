# Leaf Disease Detection
## Project description
This project uses Convolutional Neural Networks (CNN) to classify and detect various diseases in plant leaves. The model is trained on a dataset of leaf images containing both healthy and diseased leaves. By applying deep learning techniques, this project aims to automate the process of diagnosing plant health, which can be useful in agricultural applications.
## Features
**Image classification**:classifies leaf images as healthy , early blight or late blight.<br/>
**Model architecture**:Utilizes a Convolutional Neural Network for image feature extraction and classification.<br/>
**Preprocessing**: Includes preprocessing steps such as image resizing, normalization, and augmentation to improve model performance.
## Dataset 
The [dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village) used in this project consists of images of leaves. you can use any leaf disease dataset that is in a compatible format (images in labeled folders).
## Training
the model was trained on images of size 256x256 pixels, for 50 epochs using a batch size of 32 and an Adam optimizer. The training process uses a Convolutional Neural Network (CNN) architecture with image classification.
## Results
The trained model achieved an accuracy of **98%** on the test set, which highlighted the model’s ability to accurately identify and differentiate between similar categories. The model performed well overall.
