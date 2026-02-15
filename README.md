# PRODIGY_ML_05
A Deep Learning project that classifies food images into 101 categories and estimates their calorie content to help users track dietary intake and make informed food choices.

This project uses Transfer Learning with MobileNetV2 to classify food images from the Food-101 dataset.
After classification, the system estimates calorie content using a nutrition mapping dictionary.

The model enables:
Automatic food recognition from images
Estimated calorie calculation
Diet tracking support
 AI-based nutrition assistance

Dataset Name: Food-101
Source: Kaggle
Link: https://www.kaggle.com/dansbecker/food-101

Dataset Details
101 Food Categories
101,000 Images
75,000 Training Images
25,000 Test Images
Real-world food photographs

Objective
Develop a multi-class image classification model
Achieve high accuracy using Transfer Learning
Estimate calorie content based on predicted food class
Build a scalable AI-based food recognition system

Technologies Used
Python
TensorFlow / Keras
MobileNetV2 (Transfer Learning)
NumPy
Matplotlib
Google Colab

| Phase             | Accuracy |
| ----------------- | -------- |
| Initial Training  | ~75–85%  |
| After Fine-Tuning | ~85–90%  |
