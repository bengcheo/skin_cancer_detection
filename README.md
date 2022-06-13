# Detecting Melanoma through a CNN model.
> This project aims to build a CNN model which uses photographs of moles and different types of skin pigmentations to identify melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths.


## Table of Contents (Models)
1. CNN Model
2. CNN Model with data augmentation
3. CNN Model with data augmentation and class rebalancing

## General Information
### Business Problem
-  To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
### Project Objective
- The project objective is to use a CNN model to accurately detect melanoma. Data augmentation and class rebalancing will further be used to improve the model. The project will consist of three models.

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