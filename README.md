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
