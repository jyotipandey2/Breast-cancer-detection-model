Breast Cancer Detection

Breast cancer is one of the most common diseases among women worldwide. It is considered one of the leading causes of death among women. Deep Learning techniques have been previously proposed for the same. This repository contains an implementation of such a model proposed in "https://doi.org/10.1371/journal.pone.0262349".

The task is divided into two sub tasks:

Image Segmentation: U-Net is employed for segmenting breast tissue and identifying regions of interest (e.g., tumors).

Classification: A deep convolutional neural network (CNN) is used to classify the segmented regions as benign or malignant.

Features

U-Net for Segmentation:

Efficient and precise image segmentation tailored for medical imaging.
Handles complex patterns in breast tissue effectively.

Deep CNN for Classification:

Robust feature extraction for accurate classification.
Customizable architecture to fit the specific dataset.


Requirements

Python 3.8+, PyTorch 1.9.0+, Pandas, scikit-learn




Dataset 

Dataset used is DMR-IR.

The model can also be used in other publicly available datsets like BCDR.


Training Pipeline

Preprocessing:

Normalize and resize images.

Apply data augmentation for robustness.

U-Net Training:

Train on labeled masks for segmentation.

CNN Training:

Train on segmented regions for classification.

Evaluation:

Metrics: Accuracy, Sensitivity and specificity.


