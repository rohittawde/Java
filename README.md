# Raw Machine Learning
## Collection of various machine learning algotithms implemented without using any packages like SciKit or Pandas. 

- Training an artificial neural network to classify a subset of the Optical Character Recognition dataset (OCR) which consist of the pixel values of 16 x 8 image. The network implemented is a single layer neural network with a sigmoid activation function for the hidden layer. The number of hidden units for the hidden layer is a user defined input. It supports two initialization strategies viz. random initialization and all null values. Stochastic Gradient Descent is utilized to optimize the weights, wherein the number of epochs are specified as a command line argument.  
- Decision Tree - Binary classifiaction using mutual information gain as the splitting criterion. Grows trees until the splits are      statistically significant (information gain is positive) or until a user defined depth where a majority vote is implemented on the leaves.  
