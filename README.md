# MyRepository
Deep Convolutional Generative Adversarial 
Networks (DCGANs and GANs)
Design and train DCGANs using the Keras API in
Python

In this hands-on project, you will learn about
Generative Adversarial Networks (GANs) and you
will build and train a Deep Convolutional GAN 
(DCGAN) with Keras to generate images of 
fashionable clothes.  We will be using the 
Keras Sequential API with Tensorflow 2 as the 
backend.

In our GAN setup,  we want to be able to sample 
from a complex, high-dimensional training 
distribution of the Fashion MNIST images. 
However, there is no direct way to sample from
this distribution. The solution is to sample 
from a simpler distribution, such as Gaussian 
noise. We want the model to use the power of 
neural networks to learn a transformation from
the simple distribution directly to the 
training distribution that we care about. The 
GAN consists of two adversarial players: a 
discriminator and a generator. We’re going to 
train the two players jointly in a minimax game 
theoretic formulation.

SKILLS YOU WILL DEVELOP
Deep Learning
Machine Learning
Tensorflow
Computer Vision
keras

Project Overview and Import Libraries
Load and Preprocess the Data
Create Batches of Training Data
Build the Generator Network for DCGAN
Build the Discriminator Network for DCGAN
Compile the Deep Convolutional Generative Adversarial Network (DCGAN)
Define the Training Procedure
Train DCGAN
Generate Synthetic Images with DCGAN




