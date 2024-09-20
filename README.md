# NS_subwayDWT

## Summary
This repository contains the code and data used for the study *Space Generates Flow: A Novel Method for Subway Ridership Prediction for Urban Planning* submitted in *Nature Cities*. The code performs the analysis and generates the figures presented in the paper. The key focus of the project is the development of a novel method capable of forecasting subway ridership patterns without historical data and that is applicable for urban planning.

## Implementation
Our python and SQL code consists of several steps in total.
Step1.Subway Preprocessing.ipynb: Specify the spatial variable that affects the ridership pattern by specifying 500 meters near the subway station as the Station Influence Area (SIA).
Step2.subway_join.ipynb: Join the spatial variable of the subway station to the key of the ridership pattern.
Step3.DWT_transform.ipynb: Convert the daily ridership pattern of the subway station to Discrete Wavelet Transformation (DWT) to perform feature extraction.
Step4.norm_x.ipynb: Normalize the spatial variable.
Bayesian Regression240221_BD3_training.ipynb: Configure the data with the given spatial variable and dwt parameter to predict the ridership pattern.
