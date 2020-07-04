# Predict_Covid19_PGM_NumPyro

***Authors: Anders Fure Nielsen, Daniel Vigild Juhász, Jonas Søbro Christophersen & Lau Johansson*** <br /> <br />

## Overview
This repository contains hand-in assignment for the DTU course 42186 Model-Based machine learning. 

The notebook contains a implementation of Probabilistic Graph model - a linear dynamical system.

The models are implemented using the probabilistic programming library [NumPyro](https://pyro.ai/numpyro/).

![alt text](https://raw.githubusercontent.com/LauJohansson/Predict_Covid19_PGM_NumPyro/master/Predictions_image.png?raw=true)


The figure below illustates the first implemented model - a multivariate linear dynamical system.
Z: The latent states
Y's: At each timestep we sample 5 ys, that is one from each of the 5 countries. (So y1,1 denotes the sampled deaths for the first country at timestep 1.)

![alt text](https://raw.githubusercontent.com/LauJohansson/Predict_Covid19_PGM_NumPyro/master/PGM1.jpg?raw=true)


## Project scope
This project sets out to model the deaths of COVID-19 using confirmed and death statistics, along with a plethora of external covariates from the Google Mobility Report and OECD-database. From this we hope to learn more about what impacts the deaths of the virus and to what degree it impacts the deaths - in an effort to gain insight into what measures should be taken so the world is better prepared for the next pandemic. Along the way, we will also explore models that should be able to predict COVID-19 related deaths with an acceptable accuracy.


## Read more
Read our 2-page report [here](https://github.com/LauJohansson/Predict_Covid19_PGM_NumPyro/blob/master/Predicting_COVID_19.pdf) <br />
Look at the implemented models [here](https://github.com/LauJohansson/Predict_Covid19_PGM_NumPyro/blob/master/Predicting_COVID_19.ipynb)


