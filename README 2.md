# Image Classifier — Transfer Learning with Vision Transformer

**Bootcamp Assignment 3 | Session 5**

## Overview
A 5-class image classifier built using transfer learning. Instead of training a model from scratch, a pre-trained Vision Transformer (ViT) from Hugging Face is fine-tuned on a custom dataset — demonstrating how powerful models can be adapted with minimal data and compute.

## What It Does
- Generates a synthetic dataset of 500 images across 5 classes
- Fine-tunes a pre-trained ViT backbone using PyTorch
- Targets 85%+ validation accuracy
- Outputs training curves and sample predictions

## Tools & Libraries
- Python, PyTorch, Torchvision
- Hugging Face Transformers
- Matplotlib, Pillow
- Google Colab (T4 GPU)

## How to Run
1. Open `image_classifier.ipynb` in Google Colab
2. Set runtime to **T4 GPU** (Runtime → Change runtime type)
3. Run all cells top to bottom
