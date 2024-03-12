# Digit Recognizer
This project gives a detailed analysis of a 
handwritten digit recognition system which is built using K-Nearest Neighbour (KNN) algorithms and logistic regression. 
The logistic regression model gives information on the likelihood 
that a given input will fall into a particular digit class.The KNN 
method effectively utilises the proximity of data points in feature 
space for categorization purposes. Throughout the project we 
compare these two models' performances on a dataset, showing 
the advantages and disadvantages of each model.

We used MNIST dataset as the main dataset for out project. The handwritten numbers (0–9) in 
grayscale are included in this dataset. The 42,000 handwritten 
digit samples in the dataset are represented by pixel values, 
which become features for the machine learning model. Each 
image's matching digit (0–9) is assigned by the output 
variable.

![alt text](https://github.com/dahami4096/Digit-Recognizer/blob/main/MNIST-handwritten-digits-dataset-image.jpeg?raw=true)

You can access to the dataset using this link - [MINIST Dataset](https://www.kaggle.com/competitions/digit-recognizer/data/)

Using an 80/20 split, the dataset was split 
into training and test sets, with 80% of the data used for 
model training and 20% for evaluation of performance.

The project initially considered two algorithms: 
- Logistic Regression 
- K-Nearest Neighbors (KNN). 

**Logistic Regression:** 

Logistic Regression is a linear
classification algorithm used for binary and multi-class 
classification problems.
Equation (Sigmoid Function): The logistic function 1/(1+𝑒−𝑧) maps the linear combination z = ßo + ẞ1x1 + ẞ2x2 + ... + ẞnxn. It models the probability of the occurrence of a class 
using a sigmoid function and optimizes coefficients to 
minimize error.

**K-Nearest Neighbors (KNN):** 

KNN is a non-parametric 
algorithm used for classification and regression.It uses the 
'k' nearest neighbors' majority vote in the feature space to 
estimate the class of a sample.

The logistic regression model was trained for 10 epochs 
on the MNIST dataset, consisting of 60,000 training images 
and 10,000 validation images. The training history shows a 
good, steady improvement in both training and validation 
accuracy over epochs. Starting with an initial accuracy of 
91.89%, the model achieved an impressive 99.51% accuracy 
on the training set by the 10th epoch. The validation accuracy 
also shows a good improvement, reaching 96.86%.


