Project Title

Hyper-Parameter Tuning of KNClassifier on MINST dataset

Project Description.

Tune the hyper-parameters of a supervised machine learning model to achieve an accuracy score of over 97% on the testing sample.

Context

The MNIST dataset is an acronym that stands for the Modified National Institute of Standards and Technology dataset.

It is a dataset of 60,000 small square 28×28 pixel grayscale images of handwritten single digits between 0 and 9.

The task is to classify a given image of a handwritten digit into one of 10 classes representing integer values from 0 to 9, inclusively.

Data Description

The attributes of this data set include: User attributes Gender: male, female Age: below 21, 21 to 25, 26 to 30, etc. Marital Status: single, married partner, unmarried partner, or widowed Number of children: 0, 1, or more than 1 Education: high school, bachelors degree, associates degree, or graduate degree Occupation: architecture & engineering, business & financial, etc. Annual income: less than $12500, $12500 - $24999, $25000 - $37499, etc. Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8 Number of times that he/she buys takeaway food: 0, less than 1, 1 to 3, 4 to 8 or greater than 8 Number of times that he/she goes to a coffee house: 0, less than 1, 1 to 3, 4 to 8 or greater than 8 Number of times that he/she eats at a restaurant with average expense less than $20 per person: 0, less than 1, 1 to 3, 4 to 8 or greater than 8 Number of times that he/she goes to a bar: 0, less than 1, 1 to 3, 4 to 8 or greater than 8 Contextual attributes Driving destination: home, work, or no urgent destination Location of user, coupon and destination: we provide a map to show the geographical location of the user, destination, and the venue, and we mark the distance between each two places with time of driving. The user can see whether the venue is in the same direction as the destination. Weather: sunny, rainy, or snowy Temperature: 30F, 55F, or 80F Time: 10AM, 2PM, or 6PM Passenger: alone, partner, kid(s), or friend(s) Coupon attributes time before it expires: 2 hours or one day

Summary of Findings

I was able to find that for a KNClassifier the subsequent hyper parameters {'n_neighbors': 4, 'weights': 'distance'} yielded a 97.14% accuracy score on the MNINST testing data.
