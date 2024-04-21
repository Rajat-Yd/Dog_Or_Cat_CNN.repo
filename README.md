# Dog_Or_Cat.repo
- This is a CNN build on Kaggle Dataset for classification between Dog and Cat images.
# What is CNN ? :
- A convolutional neural network (CNN or ConvNet) is a network architecture for deep learning that learns directly from data.
- CNNs are particularly useful for finding patterns in images to recognize objects, classes, and categories.
- They can also be quite effective for classifying audio, time-series, and signal data.
- # About This CNN Model :
- # CNN part :
- Number of Convolutional layers used = 3, activation = "Relu" 
- Number of Pooling layers  = 3
- Number of flatten layer = 1
- # ANN part :
- One dense layer with 128 Neurons and Relu activation.
- one Hidden layer with 64 Neurons Relu activationn.
- one Output layer with one Neuron Sigmoid.
# Improvement techniques used :
- Dropout rate = 0.1
- BatchNormalization of ( 1, 256, 256, 3) per image.
# Dataset used :
- <a href = https://www.kaggle.com/datasets/salader/dogs-vs-cats>Kaggel-Dog vs Cat</a>
