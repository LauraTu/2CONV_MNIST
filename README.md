## 2CONV_MNIST
This is a project on MNIST dataset classification using tensorflow with the 2 convolutional-block neural network architecture.

### Network Architecture
+ 3 64-hidden\_dim convolutional layers, kernel\_size = 3
+ 1 maxpooling layer
+ 3 128-hidden\_dim convolutional layers, kernel\_size = 3
+ 1 maxpooling layer
+ 1 flatten layer
+ 2 dense layers with dropout, dim\_1 = 512, dim\_2=1024
+ 1 logits layer

### Parameters
+ Input_size = [784,], reshape to [28,28]
+ Batch_size = 32
+ Output_size = 10
+ Starter\_learning\_rate = 1e-2
+ Lr\_decaying\_rate = 0.96 per epoch
+ Optimizer = GradientDescentOptimizer
+ Dropout_rate = 0.1
+ Training_size = 55000
+ Validation_size = 5000
+ Testing_size = 10000

### Results
[Epoch 50]

train\_loss=0.000054, train\_acc=0.997144

valid\_loss=0.023260, valid\_acc=0.997158 

test\_loss=0.019417, test\_acc=0.997149
