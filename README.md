# Fashion MNIST Classification Using Machine Learning Algorithms and CNN


## Introduction

Image classification has continued to rise in prominence as we continue to improve on the models we use. Within this domain, object recognition and classification have taken center stage, due to its multitude of use cases.  The Fashion-MNIST dataset, derived from the articles of Zalando’s catalog of clothes, has proved itself to be a more than adequate benchmark in order to evaluate the image classification capabilities of models.This dataset consists of a training set of 60,000 examples and a training set of 10,000 examples. Each example consists of a 28x28 grayscale image associated with one of 10 labels that correlate to a certain type of clothing such as bags, ankle boots, dressers, etc. The data is distributed evenly between all of the  labels, giving us 7,000 items for each label in total. As a result, we have 70,000 rows overall, each with 785 columns, which provides us with enough data to train a strong model. We will be using this dataset to train and validate multiple learning algorithms such as random forests classifier, support vector machines, extreme gradient boosting and convolutional neural networks in order to verify which of these is best suited to image classification tasks. 

## Dataset Structure

The Fashion-MNIST dataset is split into two subsets:

- Training Set: This subset contains 60,000 images used for training machine learning models.
- Testing Set: This subset consists of 10,000 images used for testing and benchmarking the trained models.

[Click here to download the dataset.](https://www.kaggle.com/datasets/zalando-research/fashionmnist)

## Labels

Each training and test example is assigned to one of the following labels:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

# Sample Images with Labels

![](https://github.com/archit28-tamu/fashion_mnist_project/blob/main/images/sample_images_w_labels.png)

## Data Preprocessing

Starting with the distribution of the data, we observe that data is uniformly distributed with each class having 6000 images in the training dataset.

#### $$$$$ input image here $$$$$

In order to streamline the workflow, we will be reducing the dimensionality of data.
#### $$$$$ need to write stuff here $$$$$

For CNN, we will split the training data into training and validation sets, with the validation set having 10,000 rows. We will also range normalize the pixel data. This is done by dividing the pixel data by 255, as all of the pixel values lie between 0 and 255. The data is also reshaped into its intended 28x28 format so that the model reads the data as images, rather than a set of values.

## Model Selection

For model selection, we used various machine learning models like SVM, Random Forest, Logistic Regression and XGBoost.

Experiments were done on these models including hyperparameter-tuning to get accuracies of the models to choose the best performing model with best set of hyperparameters. Following are the accuracies of various machine learning models that we have used:

| **Model**          | **Accuracy**|
|:-------------------|------------:|
| SVM                | **bold**    |
| Random Forest      |  `code`     |
| Logistic Regression| _italic_    |
| XGBoost            | _italic_    |
