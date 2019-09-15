# Image_Brightness_Detection

There are two models .

Model 1:
Create a list of images in a folder and call the function evaluate_brightness .You will be returned a list of predicted labels 0 being less bright 
and 10 being more.

Model 2:
This model is created by using Convolution Neural Network . Images are augmented before passing into the model so the model will learn
the various aspect o fthe image.
After training the model .
Use model.predict and take predicted probabilities for each class labels and take the index which have maximum probability.
