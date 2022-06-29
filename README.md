Project Title

Hyper-Parameter Tuning of KNClassifier on MINST dataset

Project Description.

Tune the hyper-parameters of a supervised machine learning model to achieve an accuracy score of over 97% on the testing sample.

Context

The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset.

It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.

The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively.

Data Description

Summary of Findings

I was able to find that for a KNClassifier the subsequent hyper parameters {'n_neighbors': 4, 'weights': 'distance'} yielded a 97.14% accuracy score on the MNINST testing data.
