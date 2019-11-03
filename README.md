# Predicting-Bike-Sharing-Patterns
In this project, I had to build my first neural network and use it to predict daily bike rental ridership.  Some of the code had been provided by Udacity, but left the implementation of the neural network up to me (for the most part).  

The structure has been built out by Udacity and I've implemented both the forward pass and backward pass through the network. I've also set the hyperparameters: the __*learning rate*__, the __*number of hidden units*__, and the __*number of training passes*__ __by using only Numpy__.      
![GitHub Logo](/assets/neural_network.png)  

## Setup:
1. Create a conda environment:  
Make sure you have installed: __numpy matplotlib pandas jupyter notebook__
```
conda create --name bike-sharing python=3.7
conda install numpy matplotlib pandas jupyter notebook
```

2. Activate your environment:
* Windows:
```
activate bike-sharing
```
* Mac/Linux:
```
conda activate bike-sharing
```

3. Run the notebook server in the root directory of the project:
```
jupyter notebook
```
* The server is located in: [localhost:8888](localhost:8888/tree)
4. Open the Jupyter notebook called: [Your_first_neural_network.ipynb](/Your_first_neural_network.ipynb)
* The data comes from: [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
