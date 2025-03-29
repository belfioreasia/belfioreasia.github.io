---
title: "Hotdog Generator"
excerpt: "A DDPM model for the generaation of hot dog images. Submitted as coursework for the 'Deep Learning' postgraduate course at Imperial College London. <br/><img src='/images/DL_cw2.png'>"
collection: portfolio
---

A **Denoising Diffusion Probabilistic Model** (DDPM) is a type of *deep generative latent model* which generates new data by iteratively adding and removing noise from some prior distribution data [[1]](#1). A DDPM generally:

1. Gradually corrupts the original data with noise in a controlled way during the *forward process*
2. Allows the model to learn to *denoise* effectively during *training*  
3. Enables high-quality sample generation during the *reverse process*

![alt text](/images/DL_DDPM_architecture.png)

The implemented DDPM uses a simple CCN based **noise predictor** model which learns to predict and remove noise from images. It takes a noisy image and timestep as input and predicts the noise that was added, enabling the gradual denoising process.

![alt text](/images/DL_noising_process.png)

Come of the best generated images are shown below: 

Code Implemetation is available [here](https://github.com/belfioreasia/Deep-Learning). 


References
====
<a id="1">[1]</a>  Ho, J., Jain, A., & Abbeel, P. (2020). Denoising Diffusion Probabilistic Models. https://arxiv.org/abs/2006.11239