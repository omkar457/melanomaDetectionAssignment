Accurately detect melanoma using CNN

> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of 
melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- To detect Skin cancer accurately using images by developing CNN Model
- Skin Cancer dataset is being used
- Defining a 3 layered CNN model to train the image dataset.
- Doesn't leverage Transfer learning techniques

## Conclusions
- The 3 layer CNN model overfitted without using dropout layers(Model1)
- Introduced Drop out layers for every CNN as well Dense layer which led to underfit(Model2)
- The Class rebalance using augmentation has helped overcome underfit(Model2- built with dropouts)  
  as well as overfit(Model1- built without dropouts) . 
- The model training and validation accuracy have improved with the help of class rebalance.
- Accuracy can still be improved by training the model for more epochs using the same CNN model
- Accuracy can also be improved by using more CNN and or Dense layers in the model.

## Technologies Used
- Keras
