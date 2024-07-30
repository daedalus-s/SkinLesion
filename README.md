# Skin Lesion Classification using Transfer Learning Models

## Project Overview

This project aims to classify skin lesions using deep learning techniques and transfer learning. We utilize a benchmark dataset of skin lesion images to conduct statistical analysis and build models for accurate image classification.

## Team Members

- Anirudh Srinivasa Raghavan (as4098)
- Viswajith Menon (vm623)
- Sreeniketh Aathreya (spa44)

## Objectives

1. Use deep learning techniques to classify lesion samples from benchmark datasets accurately.
2. Provide strong insight on the statistical comparison of various pre-trained neural networks used for transfer learning and image processing.
3. Perform an in-depth analysis of how each pre-trained model performs.

## Dataset

- 10,015 dermatoscopic images from different populations
- 7 types of skin lesions:
  - Melanocytic nevus (nv)
  - Actinic keratosis (akiec)
  - Basal cell carcinoma (bcc)
  - Dermatofibroma (df)
  - Vascular lesion (vasc)
  - Malignant melanoma (mel)
  - Benign keratosis (bkl)

## Methodology

1. Dataset preprocessing and augmentation
2. Train-test split
3. Transfer learning using pre-trained models:
   - ResNet50
   - VGG16
   - ResNet152
   - DenseNet121
   - VGG19
4. Model training and evaluation

## Hyperparameters

- Learning Rate: 1e-3
- Loss Function: Cross Entropy Loss
- Optimizer: Adam
- Number of Epochs: 10
- Steps per epoch: 1024

## Evaluation Metrics

- Confusion Matrix
- Classification Report (Precision, Recall, F1 Score, Support)
- Accuracy and Loss Curves

## Results

DenseNet121 performed the best among all models tested, achieving:
- Training Accuracy: 93.045%
- Validation Accuracy: 91.327%

## Conclusion

Transfer learning proves to be extremely useful for skin lesion classification. DenseNet121 gives the best results due to its ability to generate dense feature maps and its efficiency in training.

## Future Work

- Experiment with more recent architectures
- Implement ensemble methods
- Explore techniques to handle class imbalance
