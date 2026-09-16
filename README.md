# Pneumonia Chest X-ray Classification using CNN

## Project Overview

This project focuses on developing a Convolutional Neural Network (CNN) model to classify chest X-ray images into two categories:

- NORMAL
- PNEUMONIA

The objective is to build an image classification model that can learn visual patterns from chest X-ray images and classify unseen images into the appropriate category.

## Project Workflow

1. Dataset Setup
2. Dataset Understanding
3. Image Visualization
4. Image Preprocessing
5. Training and Validation Dataset Creation
6. Data Augmentation
7. CNN Model Development
8. Model Training
9. Model Evaluation
10. Classification Report
11. Confusion Matrix
12. Sample Prediction
13. Model Saving
14. Project Conclusion

## Dataset

The project uses a chest X-ray image dataset organized into:

- Training
- Validation
- Testing

The images are classified into:

- NORMAL
- PNEUMONIA

### Dataset Distribution

| Dataset | NORMAL | PNEUMONIA |
|---|---:|---:|
| Training | 1,341 | 3,875 |
| Validation | 8 | 8 |
| Testing | 234 | 390 |

## Image Preprocessing

The images are prepared for CNN training using:

- Image resizing to 150 × 150 pixels
- Batch size of 32
- Dataset preparation using TensorFlow
- Image augmentation to improve model generalization

## CNN Model

A Convolutional Neural Network was developed for binary image classification.

The architecture includes:

- Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layers
- Output layer for binary classification

The CNN uses the following configuration:

- Optimizer: Adam
- Loss Function: Binary Cross-Entropy
- Evaluation Metric: Accuracy

Class weights are also used during training to help address the imbalance between NORMAL and PNEUMONIA images.

## Model Training

The CNN model is trained using the prepared chest X-ray training dataset.

Training performance is monitored using:

- Training accuracy
- Validation accuracy
- Training loss
- Validation loss

## Model Evaluation

The trained model is evaluated on the testing dataset using:

- Accuracy
- Classification Report
- Confusion Matrix

The classification report provides precision, recall, and F1-score for the NORMAL and PNEUMONIA classes.

## Sample Prediction

The project also includes a sample prediction step where an unseen chest X-ray image is passed through the trained CNN model to generate a predicted class.

## Model Saving

The trained CNN model is saved in Keras format:

`Pneumonia_CNN_Final.keras`

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

## Key Skills Demonstrated

- Deep Learning
- Convolutional Neural Networks
- Image Classification
- Image Preprocessing
- Data Augmentation
- Model Training
- Model Evaluation
- Classification Metrics
- Confusion Matrix
- TensorFlow & Keras

## Project Conclusion

This project demonstrates an end-to-end deep learning workflow for classifying chest X-ray images into NORMAL and PNEUMONIA categories using a Convolutional Neural Network.

The project covers the complete process from dataset preparation and image preprocessing to CNN development, model training, evaluation, sample prediction, and model saving.

## Disclaimer

This project is developed for educational and machine learning demonstration purposes. It is not intended to be used as a medical diagnostic system or as a replacement for professional medical evaluation.
