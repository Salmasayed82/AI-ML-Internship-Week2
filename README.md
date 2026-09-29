# AI/ML Internship — Week 2

## Deep Learning with PyTorch

This repository contains my Week 2 work for the AI/ML Internship.

## Tasks Completed

### Task 2.1 — Neural Network in PyTorch
Implemented a neural network workflow using PyTorch, including tensors, datasets, dataloaders, loss functions, training, and model evaluation.

### Task 2.2 — CNN Image Classifier
Built a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset.

- Training images: 50,000
- Testing images: 10,000
- Epochs: 5
- Initial test accuracy: 70.93%

### Task 2.3 — Hyperparameter Experimentation
Compared different optimizers and learning rates while keeping the CNN architecture and training epochs consistent.

| Optimizer | Learning Rate | Test Accuracy |
|---|---:|---:|
| Adam | 0.001 | 72.70% |
| Adam | 0.0005 | 70.56% |
| Adam | 0.01 | 10.00% |
| SGD | 0.001 | 30.82% |

The best-performing configuration was Adam with a learning rate of 0.001, achieving 72.70% test accuracy.

### Task 2.4 — Deep Learning Technical Report
A technical report was prepared summarizing the CNN implementation, experiments, results, and findings.

## Technologies Used

- Python
- PyTorch
- Torchvision
- CIFAR-10
- Jupyter Notebook

## Repository Contents

- `Week2_Deep_Learning_PyTorch.ipynb` — Week 2 implementation and experiments
- `Week_2_Deep_Learning_Technical_Report.pdf` — Technical report
