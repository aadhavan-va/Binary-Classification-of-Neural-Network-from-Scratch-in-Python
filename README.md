# FeedForward Neural Networks

 The  feedforward network are used to approximate some function f*. For example, a regression function y = f *(x) maps an input x to a value y. A feedforward network defines a mapping y = f (x; θ) and learns the value of the parameters θ that result in the best function approximation.
 
 ## Hidden Layers
 
  The layers between the input layer and output layers are known as hidden layers, as the training data does not show the desired output for these layers. A network can contain any number of hidden layers with any number of hidden units. A unit basically resembles a neuron which takes input from units of previous layers and computes its own activation value.
  
## Sigmoid Function

  For solving a binary classification problem, we combine Sigmoid output units with maximum likelihood. 
  As in binary classification the output layer can be a sigmoid layer as it returns a predicted value for one binary value i.e(0 or 1)
  and the other value can be calculated by using the probability formula.
  TOTAL_PROBABILITY =1

## Dataset
  1) The dataset taken for performing feed forward neural network is from sklearn.dataset library.
  2) The dataset choosen is basically  a non-linearity dataset by importing make_blobs,make_moons,make_circles etc..
  3) In this dataset two features has been taken with 1000 samples  for performing classification.
  
