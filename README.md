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
1. For my initial model, I observed overfitting here, as the validation accuracy has not increased, whereas the training accuracy has increased after 3 to 4 epochs. In addiition, the training loss continued to increase after 3 to 4 epochs, and the graphs above indicate a case of overfitting.
2. For my second model, I saw evidences of overfitting, but it was better than the previous model as both training and validation accuracy metrics slowly increased after 5 to 7 epochs. But the validation accuracy stopped increasing any further and validation loss began to increase after 5 to 7 epochs, so overfitting occured during that point. 
3. Unfortuntely for my final model I did not get rid of underfitting or overfitting, and the model with the class rebalances has overfitted but I did find the class rebalancing algorithm helpful with higher validation accuracy above 70% around 10 to 15 epochs. The higher validation accuracy means that the model with the data augmentation is a better model than the previous two models.

Personally, I am not a fan of rebalancing class by oversampling a data with fewer samples.
We need to find find more data and add to a class with fewer samples as much as possible because oversampling will not help to have a wider variance in data, as we are just repeating the same data.
We need to do more augmentation, but it may not be help the situation. 

## Technologies Used
python:  3.8.13
numpy:  1.21.5
pandas:  1.4.2
matplotlib:  3.5.2
tensorflow: 2.4.1
PIL: 9.1.1

## Contact
Created by [@bengcheo] - feel free to contact me!