# Smart Garbage Detection using Computer Vision

## Overview
Smart Garbage Detection is a Computer Vision based system that automatically detects and classifies garbage using images. The system uses Deep Learning with Convolutional Neural Networks (CNN) to identify different types of waste materials.

This project helps improve waste management systems by enabling automatic waste classification and supporting recycling processes.

---

## Problem Statement
Improper waste management is a major environmental problem in many communities. Manual waste segregation is time-consuming and inefficient.

This project aims to develop a smart system that detects garbage types automatically using image processing and deep learning techniques.

---

## Objectives
- Build a garbage detection model using CNN
- Classify waste into different categories
- Assist automated waste segregation
- Support smart city waste management

---

## Dataset

The dataset contains images of different types of garbage used to train the model.

### Classes
- Cardboard
- Glass
- Metal
- Paper
- Plastic
- Trash
dataset/
│
├── cardboard/
├── glass/
├── metal/
├── paper/
├── plastic/
└── trash/

Each folder contains images belonging to a specific waste category.

---

## Technologies Used

- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  
- Matplotlib  
- Jupyter Notebook / Google Colab

---

## Methodology

### 1. Data Preprocessing
- Image resizing
- Image normalization
- Training and validation split

### 2. Model Development
A Convolutional Neural Network (CNN) is used to learn features from garbage images.

Model components include:
- Convolution layers
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

### 3. Model Training
Training parameters:
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Epochs: 10

### 4. Prediction
The trained model predicts the waste category from an input image.

Example output:
Prediction: plastic

---

## Applications
- Smart recycling systems
- Automated waste sorting
- Smart city waste management
- Environmental sustainability systems

---

## Future Improvements
- Use larger datasets for better accuracy
- Apply transfer learning models like MobileNet or ResNet
- Deploy the model in a mobile or web application
- Integrate with IoT smart bins

---

## How to Run the Project

1. Upload the dataset to Google Colab.
2. Set the dataset path in the notebook:

```python
dataset_path = "/content/dataset"
```
3.Run the notebook cells sequentially.
4.Train the model and test predictions.




