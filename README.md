# Graduation_project

## overview
This repository contains the codes for our graduation project, which focuses on detecting anemia and hemoglobin levels using machine learning models and medical image analysis. The project is divided into three phases, described below:

##Phase 1: Anemia Detection using DenseNet
  In the first phase, we developed a machine learning pipeline to classify whether a person is anemic or not based on images of their nails, palms, and conjunctiva. We utilized the DenseNet model architecture for this task.

Data

Dataset Size: 4,100 images (after augmentation) for each part.
Image Sources: Nails, palm, and conjunctiva images.
Classes:
0: Anemic
1: Non-anemic

Results

The DenseNet model achieved the following accuracies:

Nails: 94.99%
Palm: 98.44%
Conjunctiva: 96.88%

##Phase 2: Hemoglobin Level Prediction

The second phase involves predicting hemoglobin levels based on conjunctiva images and metadata. We are currently working on building and fine-tuning the model for this task.

Data

Dataset Size: 215 images (with corresponding metadata).
Features: Conjunctiva images and relevant clinical metadata.

Current Status

Model development in progress.

Objective: Train a regression model to accurately predict hemoglobin levels.

##Phase 3: Infrared Device Integration

The final phase will involve developing a hardware device that uses infrared technology to detect hemoglobin levels. The device's output will be fed into a machine learning model for analysis.

Current Status

Development has not yet started.
