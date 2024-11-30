# Generative Adversarial Networks (GAN) for MNIST Image Generation

This project demonstrates the implementation of **Generative Adversarial Networks (GANs)** to generate synthetic MNIST-like images. GANs consist of two networks: the **Generator**, which generates fake images, and the **Discriminator**, which tries to distinguish real images from fake ones.

## Features
- **Dataset**: MNIST (handwritten digits).
- **GAN Architecture**:
  - **Generator**: A fully connected neural network that generates images from random noise.
  - **Discriminator**: A fully connected neural network that classifies images as real or fake.
- **Loss Function**: Binary Cross-Entropy Loss (BCELoss).
- **Training**: Both Generator and Discriminator are trained in an adversarial setup.
