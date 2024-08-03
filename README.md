# Stylized-Image-to-Image-Translation
Impressionist and Cubist image translation using Bicycle-GAN


The task was to create a system for transforming images from one artistic style to another,
specifically from Impressionist to Cubist. We were expected to train a hybrid model of VAEs and
GANs for this task. We chose to use the Bicycle GAN proposed in the research paper, Toward
Multimodal Image-to-Image Translation [1], which consists of two parts, namely conditional
VAE-GAN(cVAE-GAN) and conditional Latent Regressor-GAN(cLR-GAN). The overall
architecture consists of two cycles, B->z->B’ and z->B’->z’ and hence the name BicycleGAN.
Furthermore, the authors of the paper claim that the full hybrid BicycleGAN does not suffer from
mode collapse and has the highest realism score by a significant margin, which further motivated us
to choose this model over other VAE-GANs.
