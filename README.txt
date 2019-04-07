Solution Approach--

The Entire model works around Deep Learning Concept called CNN(Convolutional Neural Network).

Since Dataset is image dataset so CNN is best choice for underlying image dataset.

The Provided dataset is healthy and defected image. So we labeled dataset in to two category(1. Healthy, 0.Cracked)

Then mixedup the dataset rnadomly.

We Used keras tensorflow as backend, sklearn,numpy,matploatlib,seaborn to build the model.

In Convolutional Neural Network We have
	four convolution layer with kernel size (3,3) to detect horizontal and vertical edge
	four max pooling layer
	and Activation funtion as RELU to avoid vanishing Gradient or Exploding Gradient.
we trianed the model with batch size 32 and upto 64 Epoch.

Also calculate the accuracy of model.
	



