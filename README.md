Fine-tuning Vision Transformer (ViT) on MRI Images
This project demonstrates how to fine-tune a Vision Transformer (ViT) model for brain tumor classification using MRI images. The goal is to classify MRI images into one of four categories: Glioma, Meningioma, No Tumor, and Pituitary.

Project Overview:

Brain tumor classification is a critical task in medical imaging to assist with diagnostics and treatment planning. This project leverages the pre-trained Vision Transformer (google/vit-base-patch16-224-in21k) to achieve high classification accuracy.

Dataset:

The dataset used in this project is the Brain Tumor MRI Dataset from Kaggle.
link : https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset/data

Training Data: 5,712 images across four categories.
Testing Data: 1,311 images across four categories.
Model Architecture
The project uses a Vision Transformer (ViT), pre-trained on ImageNet-21k. This transformer-based model splits images into patches and processes them like tokens in NLP tasks.

Key features:

Patch-based processing for images.
Attention mechanism for feature extraction.
Fine-tuning for medical image classification.

Results:

Accuracy: ~95% on test data.

Visualization: Below is an example of model predictions compared to true labels:
![image](https://github.com/user-attachments/assets/e9ab5a8d-7418-440f-bc59-22f34219be8c)


Technologies Used:
Frameworks: PyTorch, Hugging Face Transformers
Libraries: scikit-learn, Torchvision, Matplotlib
Platform: Google Colab (for training) 
