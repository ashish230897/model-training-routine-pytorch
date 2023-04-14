# Training a neutral-network in Pytorch.  
  
In this tutorial notebook, a simple neural network classifier is trained to classify the MNIST dataset.  
The motivation for this notebook is the following:  
1. Train a dummy neural network on a classification dataset and learn things like: using dataloaders, learning rate schedulers, checkpointing the best model, training followed by inferencing, early stopping, gradient clipping.
2. Experiment with different hyperparameters that may increase/decrease the accuracy score:  
  a. Effect of different batch sizes on model convergence and accuracy  
  b. Effect of different learning rates on model convergence and accuracy  
  c. Effect of different activation functions on model convergence and accuracy.
