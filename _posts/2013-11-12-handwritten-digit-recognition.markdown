---
layout: post
title: Handwritten Digit Recognition
date: 2013-11-22 00:00:00 +0300
description: Handwritten Digit Recognition in C
img: js-1.png # Add image post (optional)
tags: [C, Artificial Intelligence, Machine Learning] # add tag
---
This was a project to program an handwritten digit recognizer in C. With the access to a data base with 3500 digits we started by doing some previous treatment to the images. After that we extracted 32 features from each image and we made a normalized database with them. We have implemented 2 classifiers, the K-NN and Naive Bayes. After that we have implemented the Genetic Algorithm to reduce the features needed to classify a new image and to improve the successful classification rate. After all this, with K-NN, we can successful classify 93% of the new handwritten digits with less than 20 features to analyze.
