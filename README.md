# __Handwritten Digit Recognition__

This project is a Handwritten Digit Recognition system implemented using machine learning techniques.

## __Overview__

Handwritten Digit Recognition is a classic problem in the field of machine learning and computer vision.  The goal is to take an image of a handwritten digit and determine what that digit is. The digits range from zero (0) through nine (9).

## __Dataset Used__
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning. The [dataset chosen](https://www.kaggle.com/datasets/mgoutay/traincsv) here contains 42000 samples.

## __Metrics__
We will use the accuracy score to quantify the performance of our model. The accuracy will tell us what percentage of our test data was classified correctly. The accuracy is a good metric choice because it will be easy to compare our model’s performance to that of the benchmark as it uses the same metric. Using KNN, the accuracy came out to be 96%

## __Algorithm and Technique Used__
Here KNN algorithm is used for the recoginition of handwritten digits in MNIST dataset.

The algorithm is as follows:

* Determine the parameter K = number of nearest neighbours.
* Calculate the distance between query instance and all the training samples.
* Sort the distance and determine nearest neighbours based on the kth minimum distance.
* Gather the category of nearest neighbours.
* Use simple majority of the category of the nearest neighbours as the prediction value of the query instance.

## Contributing

Contributions to the project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
