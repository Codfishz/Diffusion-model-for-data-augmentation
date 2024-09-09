# Diffusion Models-based Data Augmentation for Cell Cycle Phase Classification

This repository contains the code and resources for the project **"Diffusion Models-based Data Augmentation for the Cell Cycle Phase Classification"**. The project applies diffusion models to augment cell cycle image data and improve classification accuracy, especially in scenarios with imbalanced datasets.

## Project Overview

In biological research, imbalanced sample sizes are a common challenge, particularly in cell cycle studies where certain phases (e.g., mitotic phases) have significantly fewer samples compared to others. This project demonstrates how diffusion models can effectively augment cell cycle image data and improve classification performance, specifically in distinguishing between different phases of the cell cycle.

### Key Features
- **Data Augmentation**: Utilizes Denoising Diffusion Probabilistic Models (DDPM) to generate synthetic cell cycle images.
- **Classification Enhancement**: Demonstrates significant improvements in classification precision, particularly in minority cell phases like mitotic stages.
- **Comparison with GAN**: Shows how diffusion models perform comparably to GAN-based methods, but with simpler model structures and easier training.

## Methodology

The project involves:

- **Dataset**: A cell cycle dataset consisting of 32,266 Jurkat cell images across 7 stages: G1, S, G2, prophase, metaphase, anaphase, and telophase. These images are augmented using diffusion models to address the imbalance in the dataset.
  
- **Model**: Denoising Diffusion Probabilistic Model (DDPM) is used for image generation, adding noise during forward propagation and progressively removing it during backward propagation to generate realistic cell images.

- **Classification**: ResNet architecture is used to classify the cell cycle phases, comparing performance on the original dataset, a dataset augmented with GAN-generated images, and a dataset augmented with DDPM-generated images.
