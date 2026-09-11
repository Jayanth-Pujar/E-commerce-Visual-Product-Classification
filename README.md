# 🛍️ E-commerce Visual Product Classification

A deep learning-based computer vision project that classifies e-commerce product images into different categories using **Convolutional Neural Networks (CNNs)** and **Transfer Learning**.

## 📌 Project Overview

E-commerce platforms handle a large number of product images that need to be organized into the correct categories. Manually categorizing these images can be time-consuming.

This project explores an automated approach for classifying product images using pretrained deep learning models. The project applies image preprocessing, data augmentation, and transfer learning to build an image classification pipeline.

Different pretrained CNN architectures are explored based on their suitability for the classification task and practical deployment considerations.

## 🎯 Objectives

* Automatically classify product images into predefined categories.
* Apply computer vision techniques for image preprocessing.
* Use data augmentation to improve model generalization.
* Apply transfer learning using pretrained CNN architectures.
* Evaluate model performance using appropriate classification metrics.
* Understand the trade-off between model performance and computational efficiency.

## 🧠 Models Used

The project explores the following pretrained architectures:

* **VGG16** – Used as a baseline CNN architecture.
* **ResNet50** – Uses residual/skip connections for deeper feature learning.
* **MobileNet** – Lightweight architecture designed for efficient inference.
* **EfficientNet** – Designed to provide a balance between model accuracy and computational efficiency.

These models are used through **Transfer Learning** rather than being trained completely from scratch.

## 🔄 Project Workflow

```text
Product Image Dataset
        ↓
Data Exploration
        ↓
Image Preprocessing
        ↓
Data Augmentation
        ↓
Train / Validation / Test Split
        ↓
Transfer Learning
        ↓
┌─────────┬──────────┬───────────┬─────────────┐
│ VGG16   │ ResNet50 │ MobileNet │ EfficientNet│
└─────────┴──────────┴───────────┴─────────────┘
        ↓
Model Evaluation
        ↓
Performance & Efficiency Analysis
        ↓
Final Model
        ↓
Product Category Prediction
```

## 🛠️ Technologies & Skills

### Programming

* Python

### Deep Learning

* TensorFlow
* Keras
* Neural Networks
* Convolutional Neural Networks (CNN)
* Transfer Learning

### Computer Vision

* Image Preprocessing
* Image Resizing
* Normalization
* Data Augmentation
* Image Classification

### Models

* VGG16
* ResNet50
* MobileNet
* EfficientNet

### Data Science

* NumPy
* Pandas
* Matplotlib
* Scikit-learn

### Model Evaluation

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 📊 Model Evaluation

The models will be evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

Model efficiency will also be considered using factors such as model size and inference time.

> Results will be added after completing the experiments.

## 📁 Project Structure

```text
E-commerce-Visual-Product-Classification/
│
├── data/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_image_preprocessing.ipynb
│   ├── 03_vgg16.ipynb
│   ├── 04_resnet50.ipynb
│   ├── 05_mobilenet.ipynb
│   └── 06_efficientnet.ipynb
│
├── models/
│
├── results/
│   ├── model_comparison.csv
│   └── confusion_matrices/
│
├── images/
│
├── requirements.txt
│
└── README.md
```

## 🚀 Future Improvements

* Build a simple web interface for image prediction.
* Add more product categories.
* Fine-tune pretrained models for improved performance.
* Optimize the final model for faster inference.
* Deploy the model as an API or web application.

## 👨‍💻 Author

**Jayanth Pujar**

Data Analyst transitioning into Machine Learning, with hands-on experience in Python, SQL, Machine Learning, Deep Learning, Computer Vision, and Data Analytics.
