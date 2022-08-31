# Deep-Learning-Projects
For the above CIFAR 10 dataset I tried to use and design the VGG architecture. 

For this I first used a set of 3 convolution layers of 32 channels, here batch normalization is disabled. Then used Maxpooling layer followed by a Dropout layer.

Secondly I have used a set of 3 convolution layers of 64 channels, here I enabled batch normalization. This was then followed by Max pooling layer and then Drop out layer.

Thirdly, I used a set of 3 convolution layers of 128 channels with Batch normalization enabled, followed by Maxpooling layer and Drop out layer.

Lastly, I used a flatten layer followed by Dense layer and a dropout layer.

I used Max Pooling layer at the end of each set of convolution layer followed by Drop out layers for regularization of parameters. Used ReLU as activation fucntion. I tried using different parameters for each dropout layer to get better accuracy overall.

The entire architecture flow can be found in the model summary. With this architecture I was able to get about 95% test accuracy and 87% of validation accuracy.
