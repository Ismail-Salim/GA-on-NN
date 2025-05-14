# GA-on-NN
Genetic Algorithm Optimization of Neural Network Model

This code is part of the research study "https://doi.org/10.1016/j.fuel.2024.132673", please cite this work if the code was used. 

For the input data used in the ANN, it is published along with the publication (see link above)

00_Part1_ANN_Models.ipynb

* Run this code to construct the ANN models for each of the five studied outputs.
* Analyses include: Shap values, hyperparameters tuning optimization using Optuna. 

00_Part2_Genetic Algorithm Optimization.ipynb

* This is the Second Part, only run after constructing the ANN model from Part 1.
* The constructed ANN model from Part 1 is used as the objective function in the GA optimization
