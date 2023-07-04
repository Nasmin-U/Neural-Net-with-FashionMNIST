# Neural-Net-with-FashionMNIST

## Stem:
the image of size 28x28 pixels is divided into 196 non-overlapping patches of size 2x2, the 
weight is of size 4xd and biases are applied to each vectorised patch (where d=4). This is then stored 
in matrix of size 196x4 (where 196 is number of patches and 4=d).

## Backbone and classifier:
the backbone consists of 4 blocks; the first block uses the sigmoid 
activation function, and the rest of the blocks use the tanh activation function. Additionally, the 
mean feature is calculated and fed into a SoftMax regression classifier to output 1x10 values.
