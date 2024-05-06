
# Polyp Recognition and Segmentation

## Project Description

### Business Objective

Machine learning and deep learning technologies are rapidly advancing in the healthcare and medical sciences domain. These technologies, at times, outperform medical professionals by detecting anomalies that may not be easily discernible to the human eye. Polyp recognition and segmentation is one such technology that aids doctors in identifying polyps from colonoscopic images.

### Data Overview

The CVC-Clinic database comprises frames extracted from colonoscopy videos. It contains numerous examples of polyp frames along with corresponding ground truth labels. The ground truth images consist of masks representing the regions covered by the polyps in the images. The dataset is available in both .png and .tiff formats.

### Aim

The aim of this project is to segment polyps from colonoscopy images.

### Tech Stack

- Language: Python
- Deep Learning Library: PyTorch
- Computer Vision Library: OpenCV
- Other Python Libraries: Scikit-learn, Pandas, NumPy, Albumentations, etc.

### Approach

#### Data Understanding:
Understanding the essence of the dataset.

#### Evaluation Metrics:
Understanding the metrics used to evaluate the predictions.

#### U-Net Architecture:
Understanding the U-Net architecture and why it is widely preferred in building deep learning models for medical sciences.

#### U-Net++:
Understanding U-Net++ and how it differs from U-Net.

#### Environment Setup:
Setting up a working environment for the project.

#### Data Augmentation:
Creating new data by making modifications to the existing data.

#### Model Building:
Building the U-Net++ model using PyTorch.

#### Model Training:
Training the model (Note: GPU may be required as model training is computationally intensive).

#### Model Prediction
