# mr._clean
### I have created a ML Model for classification of 'Adult & Unwanted Images'.
####This is an approach to make web & social platforms clean and purposeful. By this way you can avoid any irrelevant content on your own platform.

## About the Model -

###
My model is based on Convolutional Neural Network (CNN) developed by using TensorFlow and Keras. Model is trained over 18,000 images of desired category. 
It has an accuracy of 82% (val_ accuracy) , 90% ( accuracy) . It has 10 epochs and 2,000 steps/epochs. 
For avoiding overfitting of model I am using Early Stopping mechanism of TensorFlow with parameters like monitor = ' val_accuracy' , patience = 3 .
I am attaching model summary for better understanding.
###
