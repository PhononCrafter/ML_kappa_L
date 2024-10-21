# ML_lattice-themal-conductivity
# Description
This repository contains the Python code and ML data used in our study to search for materials with low lattice thermal conductivity.
# Data
The target.json file contains the compound names for feature generation and the corresponding target values of lattice thermal conductivity. The feature.csv file contains the final data set for training our machine learning models; the information includes 1900 compounds each with 61 features.
# Codes
The codes for feature generation and for training machine learning models are provided in the above folders. One can go to the "Example of loading model and making prediction" folder to use our model for predicting lattice thermal conductivity. Please see further details in the folder.
# Environment
- python 3.8.19
- sklearn 1.3.2 
- matminer 0.9.0
