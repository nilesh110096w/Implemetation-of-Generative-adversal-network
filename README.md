# Implemetation-of-Generative-adversal-network
The code will implement a GAN for MNIST fashion image dataset. 

Algorithm used here is based on the fact that Generator will transform the noise data into an image which will be passed to the discriminator for score computation and then
generator will be trained to maximize that score where as discriminator will be trained to minimize the score generated by generator and maximize score of the image choosen from
the training set.

I have pytorch library for implementation and used MNIST fashion training dataset.
