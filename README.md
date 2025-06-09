Pneumonia Classification with ResNet-50

This repository contains the code and deliverables for the PGIMER Chandigarh Project Research Scientist-I screening assignment.

## Objective
To fine-tune a ResNet-50 model for distinguishing pneumonia from normal chest X-rays using the PneumoniaMNIST dataset.

## Method
- Pretrained ResNet-50 (ImageNet)
- Final layer modified for 2-class output
- Data augmentation and class weighting applied
- Adam Optimizer and Learning Rate Scheduler used 
- Evaluated with Accuracy, F1-score, and AUC-ROC

## Metrics
- Accuracy: 91.03%
- AUC-ROC: 0.9743
- F1-score (Pneumonia): 0.93

## Files Included
- `Pneumonia_ResNet5050.ipynb` – training and evaluation code
- `Pneumonia-MNIST-presentation.pptx` – 5-slide presentation
- `requirements.txt` – libraries needed
- `hyperparameters.txt` – note on LR, batch size, etc.
