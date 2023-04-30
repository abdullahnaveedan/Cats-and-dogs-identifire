# Cats-and-dogs-identifire
You have to download the latest versions of libraries.
* Keras
* Tensorflow
* Numpy
* Opencv
* Os

first to upload a dataset in jupyter or colab.

# API Token
dataset API token is !kaggle datasets download -d salader/dogs-vs-cats
# Dataset Link
dataset link is https://www.kaggle.com/datasets/salader/dogs-vs-cats

# Images Classification
Images are 25000 and the classification are:

* train images of cats are 10,000
* train images of dogs are 10,000
* test images of cats are 2500
* test images of dogs are 2500

# Working
So next is to upload dataset, unzip the folder, normalize, and use CNN layers to train your model. 
After training, take an array of 20,000 and take a sigmoid of all the data and store in array. Sort the array in assending order.
 2 classes are used:
* Dog 1
* Cat 0
 
upload the image. the model pridict the value of image and show the next 5 images values and show the data to user.
