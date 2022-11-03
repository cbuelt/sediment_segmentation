# General info

This project contains my code for the sediment segmentation challenge I took part in, during my exchange to ITMO University, St. Petersburg. The aim of the challenge is to build a machine learning model for image segmentation.

# Data

# Model
I implemented a full fledged UNet neural network with a custom loss function, which is an interpolation of the Dice-Loss and the Jaccard-Loss. In addition I added a pipeline for image transformations in order to obtain more robust results.

# Results

# Resources
Here you can find some of the resources I used to develop my model:
- [UNet - Blog article](https://towardsdatascience.com/u-net-b229b32b4a71)
- [UNet - paper](https://arxiv.org/pdf/1505.04597.pdf)
- [Blog article on Batch Normalization order](https://www.reddit.com/r/MachineLearning/comments/67gonq/d_batch_normalization_before_or_after_relu/)
- [Dropout - paper](https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf)
