# Image-classification-using-CNN
Data Loading: The MNIST dataset is loaded from keras.datasets, containing 60,000 training and 10,000 test images of handwritten digits.
Preprocessing: The images are reshaped to include a single channel (grayscale) and normalized to have pixel values between 0 and 1.
Model Architecture:
Convolutional Layers (Conv2D): Extracts features from the input images using multiple filters.
Pooling Layers (MaxPooling2D): Reduces the spatial dimensions of the feature maps.
Flattening Layer: Converts the 2D feature maps into a 1D vector to feed into the fully connected layer.
Fully Connected Layer (Dense): Learns the classification task.
Output Layer: Produces the probability distribution across 10 digits using the softmax activation function.
Training: The model is trained for 5 epochs using Adam optimizer and categorical crossentropy loss.
Evaluation: The model is evaluated on the test dataset, and accuracy is reported.
