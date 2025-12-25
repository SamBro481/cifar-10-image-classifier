# CIFAR-10 Image Classifier (PyTorch + Gradio)

A Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset to classify images into 10 object categories.  
Includes a simple and interactive web UI powered by Gradio and deployed on Hugging Face Spaces.

---

## Live Demo
Try the model directly in your browser:  
👉 **Hugging Face Space**: https://huggingface.co/spaces/sambro481/Cifar10-PyTorch-Classifier

---

## Project Overview
- Built using **PyTorch**
- Trained on **CIFAR-10** (60,000 images, 10 classes)
- Deployed using **Gradio** + **Hugging Face Spaces**
- Includes:
  - Data augmentation
  - Training & test accuracy tracking
  - Confusion matrix visualization
  - Misclassified examples display

---

## Model Architecture

A lightweight CNN:

- 3 Convolutional layers
- ReLU activations
- Max pooling for downsampling
- Fully connected classifier head

Achieved ~**80%** test accuracy.
