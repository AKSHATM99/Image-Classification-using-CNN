# mr._clean
### I have created a ML Model for classification of 'Adult & Unwanted Images'.
This is an approach to make web & social platforms clean and purposeful. By this way you can avoid any irrelevant content on your own platform.
###

## About the Model -

###
My model is based on Convolutional Neural Network (CNN) developed by using TensorFlow and Keras. Model is trained over 18,000 images of desired category. 
It has an accuracy of 82% (val_ accuracy) , 90% ( accuracy) . 
It has 10 epochs and 2,000 steps/epochs. 
For avoiding overfitting of model I am using Early Stopping mechanism of TensorFlow with parameters like monitor = ' val_accuracy' , patience = 3 .
I am attaching model summary for better understanding.
###

## Model Summary

![Summary](https://github.com/AKSHATM99/mr._clean/blob/c3f5808c677d4e49a7e11fbe3d9a2413073815cb/Model%20Summary.png)


# How to use pretrained model -
##
1. Open 'main.ipynb' file.
2. Load the model by using **load_model** function.
3. Compile the loaded model **model.compile(loss='binary_crossentropy', optimizer='adam', metrics=['accuracy'])**.
4. Now add some images in Testing folder.
5. Run model on that folder.
##
![](https://github.com/AKSHATM99/mr._clean/blob/4f780649ba1292ba43a2eef511d7ac0dd4130aea/mr.%20clean/Assets/carbon1x.png)

## Tools Used-
1. TensorFlow
2. Keras
3. Numpy
4. Python 3.8
5. Jupyter Notebook


