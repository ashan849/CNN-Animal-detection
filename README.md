# CNN-Animal-detection
# 🐾 Animal Detection using CNN (PyTorch)

This project implements a Convolutional Neural Network (CNN) in PyTorch to classify animal species from images. It includes model training, evaluation, and visualization of training performance.

---

## 📌 Project Highlights

- Built with **PyTorch**
- Custom CNN model trained to classify **3 animal classes**
- Includes **training & validation accuracy/loss plots**
- Evaluates test images using a pre-trained model
- Easy-to-follow **Jupyter Notebook** format

---

## 🧠 Model Architecture

The CNN model (`AnimalCNN`) consists of:

- Convolutional layers with ReLU activation
- MaxPooling for spatial downsampling
- Fully connected (linear) layers
- `Softmax` for final classification output

---

## 📁 Dataset

- Custom image dataset with 3 categories (e.g., cat, dog, snake)  
- Organized into:
  - `train/`
  - `val/`
  - `test/`
- Images are resized and normalized for training

> **Note**: The dataset folder structure should follow PyTorch’s `ImageFolder` format.
```bash

---

## 🚀 Getting Started

### 🔧 Requirements

- Python 3.8+
- PyTorch
- torchvision
- matplotlib
- scikit-learn
- PIL

Install requirements with:

```bash
pip install torch torchvision matplotlib scikit-learn pillow
