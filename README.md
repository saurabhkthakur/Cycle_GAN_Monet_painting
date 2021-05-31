# Cycle_GAN_Monet_painting
Project is related to Image-to-Image translation using cycle gan, dataset is taken from kaggle 

* Image-to-Image translation involves the controlled modification of an image and requires large datasets of paired images that are complex to prepare or sometimes don’t exist.
* CycleGAN is a technique for training unsupervised image translation models via the GAN architecture using unpaired collections of images from two different domains.

CycleGAN is a Generative Adversarial Network (GAN) that uses two generators and two discriminators.
We call one generator G, and have it convert images from the X domain to the Y domain. The other generator is called F, and converts images from Y to X.
Each generator has a corresponding discriminator, which attempts to tell apart its synthesized images from real ones.
