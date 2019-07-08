# Tensorflow-MNIST-


MNIST is a dataset which contains the images of digits between 0 and 9. The data is basically a categorical type in which output is the number depicted by the image. There are 70000 images which are divided into 55000 training images , 5000 validation images and 10000 testing images. I have used the tensorflow library to implement Neural networks. 

The structure of the Neural Network implemented is of the form :
Input_layer : 784 units 
Hidden_Layer_1 : 256 units 
Hidden_layer_2 : 256 units 
Output_layer : 10 units

The activation function used is the "Relu" activation function in each layer except the output layer where linear or identity function is used. 

The cost function used is the softmax cross entropy function with logits. The optimizer I have used is the AdamOptimizer with a learning rate of 0.01.
The accuracy obtained is around 96% taking the number of iterations for optimisation equal to 400. This can be changed accordingly.
The same work can be done using batches in the optimisation loop.

