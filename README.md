# Image Classification using CNN with PyTorch

## Project Description

This project implements an Image Classification model using a Convolutional Neural Network (CNN) using PyTorch.

The model is trained on the CIFAR-10 dataset to classify images into 10 different categories. Several deep learning techniques such as Batch Normalization, Dropout, and Data Augmentation were applied to improve model performance.

The project includes preprocessing, model training, evaluation, visualization, and comparison between different experiments.

---

## Problem Statement

The goal of this project is to classify images into one of the following 10 categories using Deep Learning:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Dataset

Dataset Used: **CIFAR-10**

Dataset Information:
- 60,000 color images
- 10 image classes
- 50,000 training images
- 10,000 testing images

Dataset Link:

:contentReference[oaicite:0]{index=0}

---

## Data Preprocessing

The following preprocessing techniques were applied:

- Image normalization
- Random horizontal flipping
- Random cropping (Data Augmentation)
- Conversion to Tensor
- Train/Test split

---

## Model Architecture

The CNN model contains:

### Feature Extraction Layers
- Conv2D Layer
- Batch Normalization
- ReLU Activation Function
- Max Pooling
- Dropout

### Classification Layers
- Fully Connected Layer (Dense)
- ReLU Activation
- Dropout
- Output Layer

### Enhancement Techniques Used
- Dropout
- Batch Normalization
- Data Augmentation

---

## Training Configuration

| Parameter | Value |
|------------|--------|
| Optimizer | Adam |
| Learning Rate | 0.001 |
| Batch Size | 128 |
| Epochs | 25 |
| Loss Function | CrossEntropyLoss |

---

## Experiments

Two experiments were conducted by changing the optimizer.

### Experiment 1
- Optimizer: Adam
- Learning Rate: 0.001

### Experiment 2
- Optimizer: SGD
- Learning Rate: 0.01

---

## Results

| Model | Optimizer | Accuracy | Loss |
|--------|------------|-----------|------|
| Model A | Adam | 80.65% | 0.561 |
| Model B | SGD | Add Result | Add Result |

---

## Final Performance

### Training Accuracy
**76.34%**

### Testing Accuracy
**80.65%**

### Testing Loss
**0.561**

---

## Visualizations

The following graphs are included:

- Training vs Validation Loss Curve
- Training vs Validation Accuracy Curve

These graphs help monitor the learning progress of the model during training.

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib

---

## How to Run the Project

### 1. Clone Repository

```bash
git clone YOUR_REPOSITORY_LINK
```

### 2. Install Required Libraries

```bash
pip install torch torchvision matplotlib
```

### 3. Run the Project

```bash
python main.py
```

---

## Project Structure

```text
project-folder/
│── main.py
│── README.md
│── images/
│── results/
```

---

## Conclusion

This project demonstrates the effectiveness of Convolutional Neural Networks (CNNs) for image classification tasks.

By applying enhancement techniques such as Batch Normalization, Dropout, and Data Augmentation, the model achieved **80.65% test accuracy** on the CIFAR-10 dataset.

The experiments also show how changing optimization techniques can affect model performance.
