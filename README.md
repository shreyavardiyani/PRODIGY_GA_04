# Task 4: Image-to-Image Translation using Conditional GAN (pix2pix)

## Generative AI Internship @ Prodigy InfoTech

This project implements an **Image-to-Image Translation** model using a **Conditional Generative Adversarial Network (cGAN)** based on the **pix2pix** architecture. The model learns to translate semantic building facade labels into realistic building photographs using paired image datasets.

---

### Project Overview

The objective of this project is to understand and implement the pix2pix framework for image-to-image translation. Unlike traditional GANs that generate images from random noise, pix2pix learns a mapping from an input image to a target image using paired training examples.

In this implementation, the model was trained on the **CMP Facades Dataset**, where:

- **Input:** Building Facade Label Map
- **Output:** Real Building Photograph

The project demonstrates how Conditional GANs can learn structured image translations while preserving spatial information.

### Features

- Implementation of the **pix2pix Conditional GAN (cGAN)** architecture.
- U-Net based Generator for high-quality image translation.
- PatchGAN Discriminator for evaluating local image realism.
- Image preprocessing and normalization pipeline using TensorFlow.
- Training on the CMP Facades paired image dataset.
- Generation of realistic building images from facade label maps.
- Visualization of training progress and generated outputs.

### Technologies Used

- Python
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Google Colab
- Git & GitHub

### Dataset

**Dataset Used:** CMP Facades Dataset

The CMP Facades dataset contains paired images of building facade label maps and corresponding real-world building photographs. It is widely used for benchmarking image-to-image translation models such as pix2pix.

Each sample consists of:
- **Input Image:** Semantic facade label map
- **Target Image:** Real building photograph
