# Digit_Recognition_usinf_Tensorflow_with_Mnist_Dataset
This program creates a CNN model to solve Digit Recognition Problem using Tensorflow Freamework with the Mnist Dataset. 
First the data will be loaded and the size of the images will be reshaped by adding a channel to change the image into a grayscale image and then the image will be normalized with respect to the pixel values that ranges from 0 to 255. So the numbers will be small in the range of 0 to 1 and the computation will be easier.
Then the CNN model is created . In this program the model consists of eight layers. They are two Conv2D layers , two MaxPooling2D layers , one Flatten layer , one Dropout layer and two Dense layers.
Then the model is trained with the normalised datas of the images of train data and their Loss and Accuracy vs Epoch number are plotted in two graphs respectively.
Then the testing of the model is performed with the normalised data of the test data followed by saving and loading the model created.
Finally the predictions for the normalised test data set will be given. 
