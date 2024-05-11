# Design a Multi-Layer Perceptron (MLP) Neural Network for Multi-Class Prediction
## Project Overview
This project designs a multilayer perceptron neural network using a fully connected MLP architecture. In a fully connected MLP, also known as a dense MLP, each neuron in one layer is connected to every neuron in the next layer. This type of architecture allows for complex nonlinear mappings but runs the risk of overfitting with large datasets.
The neural network has an input layer, 2 hidden layers and an output layer. For the forward pass, the activation function used in each layer and neuron is the Sigmoid function.
It does not use back propagation but leverages Cross entropy as an optimizer. This project is entirely experimental. The model is further used to predict customer churn for a bank achieving same classification metrics as the Scikit learn library MLP model.

For a detailed explanation on the theory used for this computation and an overview on how machines learn, check out the accompanying [article on medium](https://medium.com/@ayoakinkugbe/design-a-multi-layer-perceptron-mlp-neural-network-for-classification-fcd7d6a342e6)

## Model Architecture
![Blank diagram](https://github.com/ayoakin/Multilayer_Perceptron/assets/56697156/e589284b-3e9d-493f-ab8c-357a07615630)



### Code
You can find the code for this project [here](https://github.com/ayoakin/Multilayer_Perceptron/blob/main/MLP_Classification.ipynb).

File overview:

* `MLP_Classification.ipynb` - the full code from this project


## Environment Setup

### Installation
To follow this project, please install the following locally:

* Python 3.8+
* Python packages
  * pandas
  * numpy
  * matplotlib
  * sklearn
  * scipy

### Data

The data used for this implementation is the Bank Customer Churn Dataset originally on [Kaggle](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset?select=Bank+Customer+Churn+Prediction.csv).

You can download the exact file used in this project here:

* [Bank Customer Churn Dataset](https://github.com/ayoakin/Multilayer_Perceptron/blob/main/CustomerChurn.csv) - the customer churn data used in this project.
