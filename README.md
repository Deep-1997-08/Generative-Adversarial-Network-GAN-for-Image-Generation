# Generative Adversarial Network (GAN) for Image Generation

## Project Description
This project implements a Generative Adversarial Network (GAN) for generating realistic images using the CelebA dataset. The GAN consists of two neural networks: a generator and a discriminator. The generator creates fake images, while the discriminator evaluates their authenticity. The networks are trained adversarially, with the generator trying to produce more convincing fake images and the discriminator improving its ability to distinguish between real and fake images.

## Dataset
The project uses the CelebA dataset, which contains over 200,000 celebrity images with various attributes. The dataset is downloaded and preprocessed to be used in training the GAN.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Kaggle API (for downloading the dataset)

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Deep-1997-08/Generative-Adversarial-Network-GAN-for-Image-Generation.git
   cd Generative-Adversarial-Network-GAN-for-Image-Generation
