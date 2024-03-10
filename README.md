# CS-691 Assignment 2 & 3: Deep Generative Models

## Author
- **Name:** Tharun Chowdary Malepati
- **Email:** tmalepati@crimson.ua.edu

## Overview
This report presents the exploration of Deep Generative Models, focusing on Variational Autoencoders (VAEs) and Generative Adversarial Networks (GANs) to generate images from MNIST and CIFAR-10 datasets.

## Models
- **Variational Autoencoders (VAEs)**
  - Encoder: Compresses input images into a latent space.
  - Decoder: Reconstructs images from the latent space.
  - Loss Functions: Reconstruction Loss and KL Divergence.
- **Generative Adversarial Networks (GANs)**
  - Generator: Creates images to fool the discriminator.
  - Discriminator: Distinguishes between real and generated images.
  - Training: Alternates between improving generator and discriminator.

## Implementation and Hyperparameters
- **Framework**: PyTorch
- **Key Hyperparameters**:
  - Number of Epochs
  - Learning Rate
  - Batch Size
  - Latent Dimension (for VAEs)
  - Beta (for VAEs)

## Challenges and Solutions
- **Image Quality**: Improved through model tuning.
- **Mode Collapse**: Addressed by enhancing generator diversity.
- **Computational Resources**: Managed within Google Colab Pro limits.
- **Overfitting**: Mitigated with data augmentation and regularization techniques.

## Results
- **Execution Time**: VAEs and GANs showed varied performance across datasets.
- **Loss Curves**: Indicated learning stability and model convergence.
- **Generated Images**: GANs generally produced sharper images compared to VAEs, especially on MNIST.

## Conclusion
The study highlighted the capabilities and limitations of VAEs and GANs in image generation tasks. GANs tended to produce higher quality images, while VAEs offered a structured approach to understanding data distribution.

## Reflections
- The project underscored the importance of hyperparameter tuning and model selection based on task complexity.
- Computational limitations posed significant challenges, emphasizing the need for efficient resource management.
