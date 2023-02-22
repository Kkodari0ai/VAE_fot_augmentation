# VAE_fot_augmentation
Variation auto encoders used for data augmentation and train a cnn


This code defines a VAE model in TensorFlow
 and trains it on the MNIST dataset to learn 
a compressed and continuous representation
 of the images. It then generates 1000 augmented
 images by sampling from the learned latent 
space, and combines these images with the original
 images to form a larger training dataset. 
Finally, it trains a simple convolutional 
neural network (CNN) on the combined 
dataset to classify the images.
