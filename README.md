# Deep-Learning-Generative-Models

This repository contains implementations of various generative models including CGAN, DCGAN, SGAN, ACGAN, VAE, and VQVAE. Each model is built using TensorFlow/Keras and trained on the MNIST dataset. Below is a short description of each model.

## Models Included

### 1. Conditional GAN (CGAN)
**Description**: CGANs are an extension of GANs where both the generator and discriminator are conditioned on some additional information, such as class labels. This helps the generator create images corresponding to specific classes, allowing for more controlled generation.

### 2. Deep Convolutional GAN (DCGAN)
**Description**: DCGANs are GANs that incorporate convolutional and deconvolutional layers, making them effective for generating realistic images. The generator uses upsampling through transposed convolutions, while the discriminator applies convolutions to classify real vs. fake images.

### 3. Simple GAN (SGAN)
**Description**: A basic GAN model consisting of fully connected layers for both the generator and discriminator. This is a foundational implementation to understand how GANs work without the complexity of convolutional layers.

### 4. Auxiliary Classifier GAN (ACGAN)
**Description**: ACGANs extend CGANs by not only training the discriminator to differentiate real from fake images but also classifying real images into their corresponding classes. This allows the model to generate class-specific images and ensures better quality generation.

### 5. Variational Autoencoder (VAE)
**Description**: VAEs are generative models that assume a probabilistic distribution over the latent space. They generate images by sampling from a latent space distribution (usually Gaussian) and reconstructing the images from those samples.

### 6. Vector Quantized VAE (VQVAE)
**Description**: VQVAE is a variant of the VAE that quantizes the latent space to a fixed number of discrete points. Instead of continuous latent space, the model selects latent vectors from a predefined codebook, making the generated images more structured and interpretable.


