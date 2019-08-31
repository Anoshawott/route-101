# Intermediate Image Classification
### A webapp by Anosh.S



Initiate intermediate activations through capturing different images and assigning each to a class of choice. Through bootstrapping TensorFlow’s training with the pre-trained model, MobileNet, this simple “teachable machine” adopts the technique of “transfer learning”. For it to work effectively, take images that would be similar for each class e.g. several images of a different person for each class.

This custom 3-class object classifier using a camera makes use of an internal representation (activation) of the model for the image captured and hence used for classification. Utilising the module "K-Nearest Neighbors Classifer", this allows us to make predictions respective to what type of image is assigned to either of the 3 clases.
<br>
<br>
NOTE: If the web page appears messy try adjusting the zoom of your internet browser, didn't have time to create responsive webpages 😥😥

source https://www.tensorflow.org/js/tutorials/transfer/image_classification
