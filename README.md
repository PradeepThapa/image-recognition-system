[![Pylint](https://github.com/PradeepThapa/image-recognition-system/actions/workflows/pylint.yml/badge.svg?branch=main)](https://github.com/PradeepThapa/image-recognition-system/actions/workflows/pylint.yml)

## Flowers Recognition System

## Abstract
Kaggle has opensource flower dataset which contains 4242 images of flower. Each class is composed of around 800 images and it can be used for classification and clustering. The dataset has five classes of flowers: chamomile, tulip, rose, sunflower, dandelion (Mameav, 2018).
In this paper, we would like to take this opportunity to build a flower recognition system using this dataset. As this dataset is large, we have taken only 400 images per class to test KNN, SVM and AdaBoost algorithms. Due to the longer training time we conducted classification only on 4 classes: Tulip, Rose, Sunflower and Daisy.
All the parameter values for each classifier is recorded and evaluated to see the effect of parameter and its value. The best parameter is used on validation data to find out the best accuracy and use same value of parameter to train the model and test the test dataset. All three classifiers performed similar on validation dataset with the accuracy between 50-60%. However, on the test data, those classifiers could not generalize.
The SVM classifier achieved the accuracy of 46.22% on test dataset.
