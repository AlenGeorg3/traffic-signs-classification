# Sales Insights Dashboard using PowerBI

The project aims to develop a Convolutional Neural Network(CNN) model to classify traffic sign images using Keras and Python. The dataset used for this project is the German Traffic Sign Recognition Benchmark (GTSRB) dataset, which consists of more than 50,000 images of 43 different traffic signs.

The project begins with data preprocessing, which includes resizing the images, black-and-white conversion, normalizing the pixel values, and splitting the dataset into training and testing sets. Then a CNN model is designed and trained on the training dataset using Keras. The model architecture includes convolutional layers, pooling layers, and fully connected layers, followed by an activation function for classification.

To optimize the model's performance, various hyperparameters, such as learning rate, batch size, and the number of epochs, are tuned using grid search. Finally, the model is evaluated on the testing dataset and the classification accuracy is reported.

The project's outcome is a trained CNN model that can accurately classify traffic sign images. This model can be deployed in real-world scenarios, such as autonomous vehicles, to assist in the detection and recognition of traffic signs.