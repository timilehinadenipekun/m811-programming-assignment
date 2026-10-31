# MM811 Programming Assignment

Programming assignments for MM811 at the University of Alberta.

This repository contains  implementations of deep learning models for image classification, compression, reconstruction, and autoregressive modelling.

## Tasks

### Task 1: Image Classification
Implemented a modified LeNet-5 Convolutional Neural Network (CNN) for handwritten digit classification using the MNIST dataset.

### Task 2: Binary Autoencoder
Developed an autoencoder to compress and reconstruct MNIST images using a binary latent representation of size N × 3 × 4 × 4. Reconstruction quality was evaluated using Peak Signal-to-Noise Ratio (PSNR).

### Task 3: Autoregressive Models
Implemented three autoregressive approaches for generating sequences from discrete tokens:

- Sequence-to-Token using a GRU
- Sequence-to-Sequence using a Transformer
- Sequence-to-Histogram using learned token frequencies

Evaluated each model based on its ability to reproduce training sequences.

### Task 4.1: Image Generation
Implemented continuous and discrete autoencoders for image reconstruction using the CIFAR-10 dataset. Explored uniform quantization for discrete latent representations and evaluated reconstruction quality using PSNR.

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Google Colab

