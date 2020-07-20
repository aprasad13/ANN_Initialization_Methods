# Deep_Learning_Initialization_Methods

### This notebook deals with "Improving Deep Neural Networks"

Training a neural network requires specifying an initial value of the weights. A well chosen initialization method will help learning. In this notebook, we will see how different initializations lead to different results.

### A well chosen initialization can:
- Speed up the convergence of gradient descent
- Increase the odds of gradient descent converging to a lower training (and generalization) error

### What we will see in this notebook:
- Different initializations lead to different results
- Random initialization is used to break symmetry and make sure different hidden units can learn different things
- Don't intialize to values that are too large
- He initialization works well for networks with ReLU activations.

### Performance

| Model                                         | Train accuracy  | Problem/Comment             | 
| ----------------------------------------      | --------------- | ---------------------       |
| 3-layer NN with zeros initialization          | 50%             | fails to break symmetry     | 
| 3-layer NN with large random initialization   | 83%             | too large weights           | 
| 3-layer NN with He initialization             | 99%             | recommended method          | 


