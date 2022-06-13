# Understanding the demand for Bike Sharing
> This project aims to build a CNN model which uses photographs of moles and different types of skin pigmentations to identify melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.


## Table of Contents
* [0. Business Problem](#0-business-problem)
* [1. Data Understanding](#1-data-understanding)
* [2. Data Cleaning](#2-data-cleaning)
* [3. Data Analysis](#3-data-analysis)
    * [3.1 Categorical Variables](#31-categorical-variables)
    * [3.2 Numerical Variables](#32-numerical-variables)
    * [3.3 Final Summary](#33-final-summary)
* [4. Model Building](#4-model-building)
    * [4.1 Feature Engineering](#41-feature-engineering)
    * [4.2 Forward Selection](#42-forward-selection)
    * [4.3 RFE Method](#43-rfe-method)
    * [4.4 Residual Analysis of Training Data](#44-residual-analsis-of-training-data)
* [5. Making Predictions](#5-making-predictions)
* [6. Model Selection](#6-model-selection)

## General Information
### Business Problem
-  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
### Project Objective
- The project objective is to use a CNN model to accurately detect melanoma.

## Conclusions
The observations that I have made are:
1. My initial model was the strongest, which I felt that was a really strong model with 94% accuracy for training and validation accuracy metrics.
2. Despite rebalancing the classes, my model overfitted. Personally, I am not a fan of rebalancing class by oversampling a data with fewer samples.
We need to find find more data and add to a class with fewer samples as much as possible because oversampling will not help to have a wider variance in data, as we are just repeating the same data.
We need to do more augmentation, but it may not be help the situation. 

## Technologies Used
python:  3.8.8
numpy:  1.19.5
pandas:  1.2.4
matplotlib:  3.3.4
seaborn:  0.11.1
plotly:  5.5.0
statsmodels:  0.12.2
sklearn:  0.24.1

## Contact
Created by [@bengcheo] - feel free to contact me!