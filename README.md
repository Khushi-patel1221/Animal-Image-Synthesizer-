## Animal Image Synthesizer (AIS)
Animal Image Synthesizer (AIS) is a project that leverages Generative Adversarial Networks (GANs) to generate realistic images of animals using the Animal10 dataset. The project involves training an autoencoder to extract latent representations and then using these representations to train a GAN for image generation.

## Features 🎯
Autoencoder for Latent Representation: The autoencoder extracts meaningful latent representations from the images.

GAN for Image Generation: The GAN generates new animal images based on the latent representations.

Visualization: The project includes visualization of the generated images during training.

Support for CUDA: The project utilizes CUDA for GPU acceleration if available.

## Technologies 💻

PyTorch: For building and training neural networks.

Torchvision: For image transformations and dataset handling.

Matplotlib: For visualizing the generated images.

PIL: For image processing.

## Dataset 📚

Animal10: A dataset containing images of 10 different animals.

## Model Architecture 🏗️
Autoencoder

Encoder1: Two fully connected layers with LeakyReLU activation.
Encoder2: One fully connected layer with LeakyReLU activation.
GAN
Generator: Takes latent vectors as input and generates images using transposed convolutional layers.
Discriminator: Classifies images as real or fake using convolutional layers.
