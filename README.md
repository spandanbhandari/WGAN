# WGAN for Face Generation

This repository contains my Google Colab notebook implementation of a **Wasserstein Generative Adversarial Network (WGAN)** for generating face images.

## Overview
- **Architecture**: Wasserstein GAN with gradient penalty for stable training
- **Dataset**: Kaggle Anime Face Dataset
- **Goal**: Train a WGAN to generate realistic human anime facial images
- **Frameworks**:PyTorch

## Notebook
You can run the notebook directly in Google Colab using the link below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/spandanbhandari/WGAN/blob/main/WGAN%20for%20face%20creation.ipynb)

## Example Results
Here are some example outputs from the trained WGAN model:
<img width="644" height="335" alt="image" src="https://github.com/user-attachments/assets/4506b29a-c802-426f-b71e-de1ce1f351f9" />
<img width="638" height="327" alt="image" src="https://github.com/user-attachments/assets/3af7d70e-4e5d-4326-8d58-3da7809c96aa" />
<img width="642" height="336" alt="image" src="https://github.com/user-attachments/assets/2af67bf0-03d5-40a8-b324-88f97b89bf60" />




## How to Use
1. Click the **Open in Colab** button above.
2. Follow the cells in order:
   - Install dependencies
   - Load dataset
   - Define generator & discriminator
   - Train WGAN
   - Generate and visualize new faces

## References
- [Wasserstein GAN Paper](https://arxiv.org/abs/1701.07875)
- [Improved Training of Wasserstein GANs](https://arxiv.org/abs/1704.00028)
