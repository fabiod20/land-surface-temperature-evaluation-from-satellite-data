# Land Surface Temperature Evaluation from Satellite Data
This repository contains the solution proposed for the second Mini-Contest of the **Data Mining** course of *University of Naples Federico II*.
You can find more about the competition [here](https://www.kaggle.com/c/unina-data-mining-2021-minicontest-n2/overview).

The aim of the contest is to determine the Land Surface Temperature (LST) from satellite data, using data coming from the National Aeronautics and Space Administration (NASA) Landsat-8 missions.

The solution shown in the Notebook, implemented by means of *scikit-learn*, is made up of tree main stages:
- **Feature engineering**: several spectral indexes shown in the literature have been used, such has *NDVI* and *PV*.
- **Feature selection**: mainly based on features' correlation, although projection techniques such as *principal component analysis* have been used.
- **Modeling**: several models have been compared for our purpose, such as *decision tree*, *linear* and *polinomial regression*, *ridge regression*, *support vector machine* and *multi layer perceptron*, but the best one turned out to be *k-nearest neighbour*.
