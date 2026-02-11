# Vision Transformer for Image Classification

This project implements a Vision Transformer (ViT) model for image classification using PyTorch.
The model applies transformer-based self-attention mechanisms to image patches instead of
traditional convolutional layers.

## Features
- Patch embedding of images
- Learnable positional encodings
- Multi-head self-attention
- Transformer encoder blocks
- Image classification using CIFAR-10 dataset

## Dataset
- CIFAR-10
- MNIST (optional baseline)

## Technologies Used
- Python
- PyTorch
- TorchVision
- Google Colab (GPU)

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU from Runtime settings
3. Run all cells sequentially

## Results
The Vision Transformer achieves competitive accuracy on CIFAR-10 when trained with data
augmentation and the AdamW optimizer.

## References
- Dosovitskiy et al., *An Image is Worth 16×16 Words*, ICLR 2021
- PyTorch Documentation
