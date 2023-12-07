# DL_Celebrities_Detection

The code is designed for a celebrity image classification task.
The dataset contain images of 5 celebrities which include Lionel Messi, Maria Sharapova, Roger Federer, Serena Williams, and Virat Kohli.
The dataset is loaded, preprocessed, split into training and testing sets, and then used to train a convolutional neural network (CNN) model.

Data Loading and Preprocessing:
Images from directories for each celebrity is readed.
Images are resized to (128, 128) pixels.
The dataset is constructed with corresponding labels (0 to 4) for each celebrity.
The data is split into training and testing sets (80% training, 20% testing).
Images are normalized to values between 0 and 1.

Model :
The CNN model consists of 4 convolutional layers followed by max-pooling layers.
Flatten layer is used to convert the 2D feature maps to a vector.
Dense layers with ReLU activation functions are employed.
The final layer has a softmax activation for multi-class classification.

Training:
The model is compiled using the Adam optimizer and sparse categorical crossentropy loss.
Training is performed for 30 epochs with early stopping based on accuracy.

Evaluation:
Model evaluation is carried out on the testing set.
Accuracy is printed as a performance metric.

Prediction:
The model is used to make predictions on a sample image of different celebrities .
The predicted class name is printed.

Conclusion:
The code successfully implements a basic image classification pipeline for celebrity images using TensorFlow and Keras. Further improvements and fine-tuning can be made.





