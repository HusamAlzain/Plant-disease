# Palm Disease Prediction Using ResNet50 & FastAI

# Overview
This project aims to predict diseases in palm trees by utilizing deep learning techniques to process images of palm leaves.
The system helps automate the detection of diseases, enabling early intervention, improving plant health, and increasing crop yields.
The model leverages ResNet50 architecture, fine-tuned for this specific problem using FastAI library.

Project Type: Deep Learning / Computer Vision
Objective: Classify palm leaf images into different disease categories
Frameworks Used: FastAI
Deployment: Model deployed via Gradio, accessible through a web interface
Dataset: Custom dataset of palm leaf images with various diseases and healthy samples

# Dataset
The dataset consists of palm tree leaf images across several categories, including various types of diseases and healthy samples.
It has been collected by the team, with a supervision of an agricultural engineer
Dataset can be found here https://www.kaggle.com/datasets/husamalzain/palm-disease-dataset/data

# Model Architecture
The model is built upon the ResNet50 architecture, pre-trained on ImageNet. ResNet50 was chosen because of its strong performance in image classification tasks.
We fine-tuned the model on the palm leaf dataset to classify between healthy and diseased samples.

# Key Model Components
Base Model: ResNet50 (pre-trained on ImageNet)
The ResNet50 architecture allows for extracting complex features from the image data, which is essential in differentiating subtle differences between disease types in palm leaves.

# Results
The final model achieved an overall accuracy of 94%, showing strong performance across the different disease categories.

To access the notebook:
https://colab.research.google.com/gist/HusamAlzain/c4020362e4735f574787c2981131bedc/palm-disease-notebook.ipynb
