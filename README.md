# Landmark Classification & Tagging for Social Media
In this project, I build the Convolutional Neural Network (CNN) module to build a landmark classifier. This project is part of [deep learning nanodegree program](https://www.udacity.com/course/deep-learning-nanodegree--nd101?utm_source=gsem_brand&utm_medium=ads_r&utm_campaign=12907727449_c&utm_term=121152412746&utm_keyword=nanodegree%20deep%20learning_e&gclid=Cj0KCQiAuvOPBhDXARIsAKzLQ8FAvwPPKAF_H4dDtoM72ul1lKBTcQeUHrankyOSeiNxB5F-l5LHvIoaAmsAEALw_wcB) with Udacity

# Steps of the project include:

1) *Create a CNN to Classify Landmarks (from Scratch)* - Here, you'll visualize the dataset, process it for training, and then build a convolutional neural network from scratch to classify the landmarks. You'll also describe some of your decisions around data processing and how you chose your network architecture.

2) *Create a CNN to Classify Landmarks (using Transfer Learning)* - Next, you'll investigate different pre-trained models and decide on one to use for this classification task. Along with training and testing this transfer-learned network, you'll explain how you arrived at the pre-trained network you chose.

3) *Write Your Landmark Prediction Algorithm*- Finally, you will use your best model to create a simple interface for others to be able to use your model to find the most likely landmarks depicted in an image. You'll also test out your model yourself and reflect on the strengths and weaknesses of your model.

# Dataset
The landmark images are a subset of the Google Landmarks Dataset v2. The dataset can be obtained using this [link](https://www.kaggle.com/google/google-landmarks-dataset).

## Project Overview

Welcome to the Convolutional Neural Networks (CNN) project!
In this project, you will learn how to build a pipeline to process real-world, user-supplied images and to put your model into an app.
Given an image, your app will predict the most likely locations where the image was taken.

By completing this lab, you demonstrate your understanding of the challenges involved in piecing together a series of models designed to perform various tasks in a data processing pipeline. 

Each model has its strengths and weaknesses, and engineering a real-world application often involves solving many problems without a perfect answer.

### Why We're Here

Photo sharing and photo storage services like to have location data for each photo that is uploaded. With the location data, these services can build advanced features, such as automatic suggestion of relevant tags or automatic photo organization, which help provide a compelling user experience. Although a photo's location can often be obtained by looking at the photo's metadata, many photos uploaded to these services will not have location metadata available. This can happen when, for example, the camera capturing the picture does not have GPS or if a photo's metadata is scrubbed due to privacy concerns.

If no location metadata for an image is available, one way to infer the location is to detect and classify a discernable landmark in the image. Given the large number of landmarks across the world and the immense volume of images that are uploaded to photo sharing services, using human judgement to classify these landmarks would not be feasible.

In this project, you will take the first steps towards addressing this problem by building a CNN-powered app to automatically predict the location of the image based on any landmarks depicted in the image. At the end of this project, your app will accept any user-supplied image as input and suggest the top k most relevant landmarks from 50 possible landmarks from across the world.


