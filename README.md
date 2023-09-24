# KaggleDigitRecognizer
Kaggle has an ongoing machine learning competition where users compete to predict the labels of handwritten digits from the MNIST dataset with the most accuracy. I am currently participating in the competition and using it as a way to learn the PyTorch machine learning library. So far my best model is a CNN trained with batch normalization, dropout, and online data augmentation of the training set. It has an accuracy of `99.278%` on Kaggle's MNIST test set.

As part of this I learned the basics of PyTorch including:
 - Working with tensors
 - Using the DataLoader and Dataset classes to make my own custom datasets
 - Defining a custom model (both vanilla NNs and CNNs) 
 - Data augmentation for images
 - Training a model over multiple epochs with batches and Adam
 - Validating the model with a validation set
 - Saving the best model as I train and loading it afterwards for testing
 - Stopping training once the model begins to overfit using early stopping w/ patience
