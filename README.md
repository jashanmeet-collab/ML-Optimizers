# ML-Optimizers
**Exploring different optimization approaches for several class of ML classifiers**

## 1. Project Members
- Jashan Meet (MBA, UC-Riverside)
- Sandeep Singh Sandha (CS-PhD, UCLA)

## 2. Project Goals
In this project, we explore the different kinds of optimizers soving the loss functions of machine learning classifiers. Each optimizer has its own strenghts and weakness. Through our exploration, we show the accuracy vs complexity (runtime, effort) tradeoff. 

## 3. Current Status
We consider the following optimizers for linear regression. 

### a. Directly solving the Linear Regression analytical equation 
In this, we use pseudo inverse from numpy.

### b. Grid-search based optimizer.
We used grid search to explore and find optimum solution to the model parameters.

### c. Random search optimizer
We use randomly explore the parameter search space of model, and limit our search by maximum allowed iterations (compute budget). This random exploration is used to find decide the best solution found of the model parameters. 
