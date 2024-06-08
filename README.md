# MNIST_Classifier_SGD
MNIST Classifier using Stochastic Gradient Descent

## Details
This Python notebook implements a classifier for the MNIST dataset, achieving an accuracy of approximately 96.6%. The classifier itself is quite basic, employing Stochastic Gradient Descent (SGD) with a Perceptron loss and Elastic Net regularization. By itself, the classifier achieves around 80% accuracy. However, specific preprocessing steps boost the performance significantly.

## List of preprocessing steps
- __Augmentation of Data__ : Expanding the dataset to approximately 110,000 samples.
- __Zoneing__ : Combining information from each 2x2 grid in an image into a single pixel, effectively downsampling the image. A dimention reduction that turns each 28x28 image into a 14x14 one _without the loss of information_.
- __PCA__ : Reducing the data to about 30 principal components.
- __Polynomial Feature__ : A degree 2 polynomial feature combination is employed to capture the dependencies between features, which naturally occur in images.

## List of model parameters
- Stochastic Gradient Descent
- Perceptron Loss
- Elastic Net Regularization

