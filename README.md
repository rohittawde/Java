# Raw Machine Learning
## Collection of various machine learning algotithms implemented without using any packages like SciKit, Pandas etc. 

- **Decision Tree** - Binary classifiaction using mutual information gain as the splitting criterion is implemented. It grows the tree until the splits are statistically significant (information gain is positive) or until a user defined depth where a majority vote is implemented on the leaves. 

- **Multinomial Logistic Regression** - Extracted flight information from Airline Travel Information System (ATIS) dataset by means of multinomial logistic regression. Implemented two models where the probability distribution over the output tag is based on the current word and where is based on the current, previous as well as the next word.

- **Neural Network** - Trained an artificial neural network to classify a subset of the Optical Character Recognition dataset (OCR) which consist of the pixel values of 16 x 8 image. The network implemented is a single layer neural network with a sigmoid activation function for the hidden layer. The number of hidden units for the hidden layer is a user defined input. It supports two initialization strategies viz. random initialization and all null values. Stochastic Gradient Descent is utilized to optimize the weights, wherein the number of epochs are specified as a command line argument.   

- **Hidden Markov Model** - Implemented an algorithm to determine the initialization, transition and emission probabilities for a Hidden Markov Model. Determined part of speech tags using forward backward algorithm.

- **Refinforcement Learning** - Trained an agent to solve a maze using Q learning and value iteration algorithm. Implemented all of the functions needed to initialize, train, evaluate, and obtain the optimal policies and values with these reinforcement learning algorithms.
