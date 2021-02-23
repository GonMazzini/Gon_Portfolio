####  (Many of my repositories regarding Machine Learning, Optimization problems, Wind Loads and Reliability analysis can be seen in https://github.com/GonMazzini )

# This Portfolio contains a brief overview of some Machine Learning models related to Wind Energy.



### [Classification: Random Forest and ANN models in order to predict the status of the WTG.](https://github.com/GonMazzini/EDP-data)
* Data set from EDP.
* SCADA data from Wind Turbine Generators (WTG).
* inputs for the model: Wind Speed, Power, Generator RPM, Blade Pitch Angle.
* ANN with 2 hidden layers (12,12), a batch size of 144 and ReLu as activation func.
* Confusion matrix showing a high accurancy for both models.

![image](images/clasification.png)


### Clustering: Using the K-mean clustering algorithm and Gaussian Mixture (GM) model to classify the points in the Power Curve.
* Unsupervised learning problem.
* K-mean clustering exhibits a more reasonable clutering.
![image](images/clustering%20gaussian.png)



# [Regression - KNN regressor surrogate load model for Blade Flapwise Moment.](https://github.com/GonMazzini/Reliability-Analysis)
* Data set from "wind2loads" model (DTU)
* inputs: Wind Speed, Turbulence and Shear.
* KNN model with Cross-Validation (5 folds) in order to find the optimum value of K.
* Python implementation for First Order Reliability Method (FORM) and Monte Carlo as well using the loads output from the previous model.


![image](images/KNN%20regressor.png)

![image](images/Reliability%20plot.png?raw=true)
