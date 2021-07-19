# HyperspecFeatureSelection
HyperspecFeatureSelection uses machine-learning based methods to identify optimal wavelengths for the classification of peanut stem rot. This methodology can be adapted for determining the spectral signatures of other plant-disease systems.

# Introduction
Hyperspectral sensors are a promising tool for automated plant disease detection. However, the high dimensionality and redundancy of hyperspectral data pose a challenge for the data analysis to identify informative wavelengths directly related to pathogen infection. Our work addresses this challenge using multiple machine learning and feature selection methods to determine the optimal wavelengths as spectral signatures of plant-pathogen infection and disease development.

# Dependence and requirements
## Requirements
Python (v3.0 or more; Developed and tested with version 3.7.10)

sklearn (python package; Developed and tested with version 0.24.1)

pandas (python package; Developed and tested with version 1.2.3)

numpy (python package; Developed and tested with version 1.19.2)

xgboost (python package; Developed and tested with version 1.3.3)

# Instructions
## Folder description
○ inputs: this folder is used to store the master spectral file (.csv) after pre-processing steps

○ scripts: this folder is used to store scripts developed by the project team

○ results: this folder is needed to store the generated result files

## Script description
○ ms_s20_peanut_ssr_classification_ml_052521.ipynb: This script is to compare different machine learning algorithms using Python for the classification of peanut stem rot at different stages of disease development

○ ms_s32_peanut_ssr_feature_selection_distance_052521.ipynb: This script is for testing different feature selection methods in the scikit-learn library to select the top 10 wavelengths with and without a customized distance for the classification of peanut stem rot

# Publication
Wei, X.; Johnson, M.A.; Langston, D.B., Jr.; Mehl, H.L.; Li, S. Identifying Optimal Wavelengths as Disease Signatures Using Hyperspectral Sensor and Machine Learning. Remote Sens. 2021, 13, 2833. https://doi.org/10.3390/rs13142833
