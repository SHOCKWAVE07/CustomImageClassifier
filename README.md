# CustomImageClassifier

### Install required packages

### Create a Data Pipeline

### Validate the images from the dataset
* imghdr is used to verify the image extensions
* imgages that do not support the format are deleted

### Load the dataset
* tf.keras.utils.image_dataset_from_directory is used to load the dataset from directory
* data is loaded into batches

### Preprocessing
* Image pixels are brought down to [0,1] from [0,255]

### Split the dataset in train-val-test

### Model Building
* tensorflow.keras.models - Sequential
* tensorflow.keras.layers - Conv2D, MaxPooling2D, Dense, Flatten
* Activation function - Relu & Sigmoid
* Loss Fucntion - BinaryCrossEntropy
* Optimizer - Adam

### Model Evaluation
* Accuracy, Precision and Recall

### Save the Model 
