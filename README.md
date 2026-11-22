# Animal Image Classification

## Project Overview
Deep Learning project for classifying 37 cat and dog breeds using the Oxford-IIIT Pet Dataset.

## Dataset
- Dataset: Oxford-IIIT Pet
- Number of classes: 37
- Training images: 3,680
- Testing images: 3,669

## Models
- Model A: Custom CNN (AnimalCNN)
- Model B: Pretrained ResNet18

## Experiments
- Learning rate comparison (0.0001 vs 0.001)
- Data augmentation vs no augmentation
- Repeated experiments with 3 random seeds

## Results
- ResNet18 Test Accuracy: 87.00%
- ResNet18 Test Macro F1: 86.86%
- No Augmentation Test Accuracy: 88.20%
- No Augmentation Test Macro F1: 87.98%

### 3-Seed Evaluation
- Mean Accuracy: 87.36% ± 0.42%
- Mean Macro F1: 87.11% ± 0.43%

## Technologies
- Python
- PyTorch
- Torchvision
- Scikit-learn
- Kaggle GPU (Tesla T4)
