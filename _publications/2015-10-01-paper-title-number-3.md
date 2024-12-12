---
title: "Independent Thinking: A Novel Approach to Model Distribution Training and Integration"
collection: publications
excerpt: 'This paper is about a new train framework'
date: 2025


---
This work is still in progress, and we have completed most of the experiments.

Abstract:
We propose a new training method that enables multiple models, trained separately on different subsets of the dataset, which make it possible to aggregate their results using a simple approach. On the MNIST, Cifar-10, Cifar-100, and our custom-created text dataset, the aggregated results achieved over 99% accuracy on the training set which is considerably better than results of individual models.
We train the model using a Multilayer Perceptron (MLP) architecture consisting of four fully connected layers, without making any modifications to the original model structure. To enable aggregation through a simple method, on one hand, the model needs to achieve high accuracy on seen data; on the other hand, we need to be able to identify, through a simple method, which model is sensitive to the current data. To achieve this, we impose certain constraints on the models' outputs, ensuring that the data they have seen is more regulate, while making the outputs for unseen data more chaotic. In detail, we impose the following additional constraints during training, alongside the original loss function: on one hand, we aim to increase the variance of the outputs across different classes, and on the other hand, we seek to reduce the variance of the outputs within the same class. 

