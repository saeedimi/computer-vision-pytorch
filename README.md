# Computer Vision with PyTorch

A collection of practical **Computer Vision** projects implemented using **PyTorch**. This repository covers the fundamentals of Convolutional Neural Networks (CNNs), transfer learning with pretrained models, and real-world image classification applications. Each notebook has been reorganized, documented, and expanded to demonstrate modern deep learning workflows for computer vision.

![CNN Architecture](images/CNN.png)

---

# 🚀 Repository Overview

This repository contains practical computer vision projects built with **PyTorch**, covering convolutional neural networks, transfer learning, and image classification through reproducible, well-documented notebooks.

---

# ✨ Project Highlights

- Convolutional Neural Networks (CNNs) implemented with PyTorch
- Transfer learning using pretrained AlexNet
- End-to-end image classification workflows
- GPU-ready training pipelines
- Automatic dataset downloading for reproducibility
- Well-documented notebooks suitable for learning and experimentation

---

# 📚 Topics Covered

- Convolutional Neural Networks (CNNs)
- Convolution and feature extraction
- Pooling operations
- Image classification
- Transfer learning
- Feature extraction using pretrained models
- Fine-tuning pretrained CNNs
- Data augmentation
- Data normalization
- Weight decay
- Dropout
- Preventing overfitting
- Model evaluation
- GPU acceleration with CUDA
- Visualizing convolution kernels

---

# 🛠️ Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Pillow (PIL)
- gdown

---

# 📂 Repository Structure

```text
computer-vision-pytorch/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_cnn_fundamentals.ipynb
│   ├── 02_transfer_learning.ipynb
│   └── 03_hand_gesture_recognition.ipynb
│
├── images/
│   └── CNN.png
│
├── datasets/
└── models/
```

---

# 📖 Notebooks

## Notebook 1 — CNN Fundamentals

### Overview

This notebook introduces the core concepts of Convolutional Neural Networks (CNNs) using PyTorch. It explores convolution operations, pooling layers, feature extraction, GPU acceleration, and image classification while building an intuitive understanding of how CNNs learn visual representations.

### Topics Covered

- Convolutional Neural Networks (CNNs)
- Convolution operations
- Feature extraction
- Pooling layers
- Image classification
- GPU acceleration with CUDA
- Building CNNs in PyTorch
- Visualizing convolution kernels

### Notebook

`notebooks/01_cnn_fundamentals.ipynb`

---

## Notebook 2 — Transfer Learning with PyTorch

### Overview

This notebook demonstrates transfer learning for image classification using pretrained convolutional neural networks in PyTorch. It explores feature extraction with AlexNet, visualizes learned representations, applies transfer learning to image datasets, and investigates techniques for improving model generalization, including data normalization, data augmentation, weight decay, and dropout.

![CNN Architecture](images/TR.png)

### Topics Covered

- Transfer learning
- AlexNet
- Feature extraction
- Pretrained CNNs
- Image classification
- Data normalization
- Data augmentation
- Weight decay
- Dropout
- Preventing overfitting

### Notebook

`notebooks/02_transfer_learning.ipynb`

---

## Notebook 3 — Hand Gesture Recognition

### Overview

This notebook presents an end-to-end hand gesture recognition pipeline using convolutional neural networks in PyTorch. It covers dataset preprocessing, model training, performance evaluation, and prediction on unseen images while demonstrating a complete deep learning workflow for image classification.

### Topics Covered

- Image preprocessing
- Hand gesture recognition
- Convolutional Neural Networks
- Dataset preparation
- Model training
- Performance evaluation
- Prediction and inference
- PyTorch workflows

### Notebook

`notebooks/03_hand_gesture_recognition.ipynb`

---

# 📦 Datasets

Some notebooks require image datasets that are **not included** in this repository because of their size.

To keep the repository lightweight and easy to clone, datasets are downloaded automatically the first time the corresponding notebook is executed.

| Notebook | Dataset |
|----------|---------|
| **01 – CNN Fundamentals** | Built-in examples |
| **02 – Transfer Learning** | Lightweight Flower Classification Dataset (downloaded automatically from Google Drive) |
| **03 – Hand Gesture Recognition** | Hand Gesture dataset *(downloaded automatically)* |

---

# 🎯 Learning Objectives

Throughout this repository, I explore how to:

- Understand convolutional neural network architectures.
- Extract visual features using convolutional filters.
- Build CNN models using PyTorch.
- Train and evaluate image classification models.
- Apply transfer learning using pretrained networks.
- Fine-tune pretrained models for new datasets.
- Improve model generalization using practical regularization techniques.
- Develop complete computer vision pipelines.

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Miladsaeedi70/computer-vision-pytorch.git
```

Navigate to the project:

```bash
cd computer-vision-pytorch
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks in numerical order:

1. CNN Fundamentals
2. Transfer Learning
3. Hand Gesture Recognition

Datasets are downloaded automatically when required, so no manual dataset setup is necessary.

---

# ⭐ About

This repository showcases practical computer vision projects developed with **PyTorch**. It demonstrates modern deep learning workflows for convolutional neural networks, transfer learning, and image classification through reproducible, well-documented implementations.

The notebooks have been reorganized and modernized to improve readability, reproducibility, and compatibility with current versions of PyTorch and Python.

---

# 📄 License

This repository is intended for educational and portfolio purposes.