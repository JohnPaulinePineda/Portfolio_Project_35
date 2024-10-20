# [Supervised Learning : Characterizing Life Expectancy Drivers Across Countries Using Model-Agnostic Interpretation Methods for Black-Box Models](https://johnpaulinepineda.github.io/Portfolio_Project_35/)

[![](https://img.shields.io/badge/R-black?logo=R)](#) [![](https://img.shields.io/badge/RStudio-black?logo=RStudio)](#)

Life expectancy is a statistical measure that represents the average number of years a person is expected to live from birth, assuming current mortality rates remain constant along the entire life course. It provides an estimation of the overall health and well-being of a population and is often reflective of the local conditions encompassing numerous factors including demographic, socio-economic, healthcare access and healthcare quality. This [case study](https://johnpaulinepineda.github.io/Portfolio_Project_35/) aims to develop an interpretable regression model which could provide robust and reliable estimates of life expectancy from an optimal set of observations and predictors, while delivering accurate predictions when applied to new unseen data. Data quality assessment and model-independent feature selection were conducted on the initial dataset to identify and remove cases or variables noted with irregularities, in adddition to the subsequent preprocessing operations most suitable for the downstream analysis. Multiple regression models with optimized hyperparameters were formulated using Stochastic Gradient Boosting, Cubist Regression, Neural Network, Random Forest, Linear Regression and Partial Least Squares Regression. Model performance among candidate models was compared using the Root Mean Square Error (RMSE) and R-Squared metrics, evaluated internally (using K-Fold Cross Validation) and externally (using an Independent Test Set). Post-hoc exploration of the model results to provide insights on the importance, contribution and effect of the various predictors to model prediction involved model agnostic methods including Dataset-Level Exploration using model-level global explanations (Permutated Mean Dropout Loss-Based Variable Importance, Partial Dependence Plots) and Instance-Level Exploration using prediction-level local explanations (Breakdown Plots, Shapley Additive Explanations, Ceteris Paribus Plots, Local Fidelity Plots, Local Stability Plots).

<img src="images/Summary_0.png?raw=true"/>

<img src="images/Summary_1.png?raw=true"/>

<img src="images/Summary_2.png?raw=true"/>

<img src="images/Summary_3.png?raw=true"/>

<img src="images/Summary_4.png?raw=true"/>

<img src="images/Summary_5.png?raw=true"/>

<img src="images/Summary_6.png?raw=true"/>
