# Plant Disease Detection System

## To avoid Overshooting Loss function:

- Choose small learning rate default 0.001 here we have taken 0.0001
- There may be chance of underfitting so increase number of neuron
  - Add more Convolutional Layer to extract more feature from images there may be possibilty that model unable to capture relevant feature or model is confusing due to lack of feature so feed with more feature
- There may be change of overfitting so we can add some dropout layers to feed the connected neural network, before Flatten layer and before Output layer.

## To avoid High numbers of parameters:

- remove padding = 'same' from second convolutions layers in each layer, so it make the model lighter and easier in training. it will use the default 'valid'
