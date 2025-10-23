# Cats vs Dogs Image Classification
This project implements a Convolutional Neural Network (CNN) to classify images of **cats** and **dogs**. The model is trained using TensorFlow and Keras, and predictions are generated for a separate test dataset.

## Project Overview
- **Goal:** Classify images into **cat** or **dog** categories.
- **Dataset:** Labeled images (`dog.x.jpg` / `cat.x.jpg`) for training and separate unlabeled test images.
- **Approach:**
  - Data preprocessing with `ImageDataGenerator`
  - Training/validation split with stratification
  - CNN with 3 convolutional + pooling layers, fully connected layers, and dropout
  - Sigmoid output for binary classification
 
## Model Performance
- **Training Accuracy:** ~81%  
- **Validation Accuracy:** ~80%  

> The model demonstrates a strong ability to distinguish between cats and dogs with high confidence.

## Sample Predictions
The model predicts the labels on test images and visualizes a subset:

<img width="1117" height="790" alt="image" src="https://github.com/user-attachments/assets/ccd68474-9100-42c8-bfe1-d97a106b77ba" />

## Outcome
* Achieved a validation accuracy demonstrating strong model performance on unseen data.
* Successfully predicted unseen test images, correctly classifying cats and dogs with high confidence.
* Visualized sample predictions effectively using images with predicted labels and probabilities.

## Tech Stack
- Dataset: [Kaggle Dogs vs Cats Dataset](https://www.kaggle.com/c/dogs-vs-cats)
- Python Libraries: `TensorFlow/Keras`, `Pandas`, `NumPy`, `Sk-Learn`, `Matplotlib`, `OS`  
- Concepts: CNNs, Image Preprocessing, Data Augmentation, Binary Classification

## License
MIT License © 2025 Riddhi Bajaj
