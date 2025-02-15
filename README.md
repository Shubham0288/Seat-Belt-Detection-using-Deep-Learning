# Seat-Belt-Detection-using-Deep-Learning
# Overview
-This project uses a Convolutional Neural Network (CNN) to detect whether a person is wearing a seat belt or not from images. The model is trained using TensorFlow/Keras with a dataset of 4030 images, enhanced using ImageDataGenerator for data augmentation.

# Dataset
-The dataset consists of 4030 images categorized into two classes:
    1)With Seatbelt
    2)Without Seatbelt
Images are preprocessed and augmented using ImageDataGenerator.

# Model Architecture
  CNN Layers:
      1)Three convolutional layers with ReLU activation
      2)Max-pooling layers for feature extraction
      3)Flattening and fully connected Dense layers
-Final sigmoid activation for binary classification
-Optimizer: Adam
-Loss Function: Binary Crossentropy
-Evaluation Metric: Accuracy
# Results
-Achieved 85% accuracy on validation data.
-The model effectively classifies seat belt usage.
