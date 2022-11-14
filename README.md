# Generative Adversarial Network

This repository contains various Generative Adversarial Network implementations with PyTorch. 


>### CycleGAN

A detailed implementation of CycleGAN that is composed of Generators and  Discriminators. The Generator is constructed from an **Encoder**, **Decoder** and a series of **Residual Blocks**. Additionally, the adversarial losses and cycle consistency losses, and train processes of the Discriminator and Generator are explained in PyTorch. The provided notebook's objective is to work on image-to-image translation. The image translation discussed is to read an image from a set 𝑋 and transform it so that it looks as if it belongs in set 𝑌. For this purpose, a set of images of Yosemite National Park taken either during the summer or winter is studied. The seasons are the two domains that are worked on.  

![cyclegan](https://user-images.githubusercontent.com/46245117/201660760-09ae9d48-b208-4555-8e4e-d2bfb0b42315.PNG)

>### DCGAN on Street View House Numbers

Implementation of Deep Convolutional GAN to generate realistic House Number images. The provided notebook discusses the feature space that is learned by the Generator. 

>### DCGAN on Face Generation

Implementation of Deep Convolutional GAN to generate realistic faces. Tips on training a GAN are discussed and the outcome of the faces and the plotted losses are examined to further enhance the model.  

>### GAN

A simple implementation of GAN with fully connected layers to explain how GANs work.

The above content is my implementation of the exercises and the projects from the Udacity Deep Learning Course notebooks.
