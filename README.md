# mnist
Trains a neural network model to classify on mnist dataset
It uses tf.keras, a high-level API to build and train models in TensorFlow.

Loading the dataset returns four NumPy arrays:
1. The train_images and train_labels arrays are the training set—the data the model uses to learn.
2. The model is tested against the test set, the test_images, and test_labels arrays.

The images are 28x28 NumPy arrays, with pixel values ranging between 0 and 255. 
The labels are an array of integers, ranging from 0 to 9.

class_names = ['T-shirt/top', 'Trouser', 'Pullover', 'Dress', 'Coat', 
               'Sandal', 'Shirt', 'Sneaker', 'Bag', 'Ankle boot']
               
               
The first layer in this network, tf.keras.layers.Flatten, transforms the format of the images from 
a 2d-array (of 28 by 28 pixels), to a 1d-array of 28 * 28 = 784 pixels.               
               
