---
title: "Machine Learning 101"
date: 2020-08-01T11:34:07+05:30
draft: false
categories:
- machine learning
tags : 
- machine learning 

---


# The mystery behind the field of Machine Learning:

Traditionally, as computer programmers, our job is to provide instructions to the computer to perform an action. We do this via a programming language.

In Machine Learning, the computer is not provided clear instructions. Rather, it is given a set of template data(formally known as *model* in the ML world). The computer attempts to *learn* instructions in accordance to the provided model automatically.

---

Now learning can be classified into 3 types, namely : 

## Supervised Learning
Here, learning occurs on the basis of pre-provided pairs of data(*labeleed training data*). By pair, we mean, containing an input object(vector) and a desired output value(called the supervisory signal).

A supervised learning algorithm, analyzes the training data,and provides an inferred function that can be used for mapping new examples.

A simple example can be predicting the house prices.
Provided the past prices and the house area, the algorithm can predict for a given house area, what will be the price.


## Unsupervised Learning
No preexisting labels. This is the fundamental difference.
In unsupervised learning, prediction is done using modelling of probability densities over provided inputs, rather than making use of human labelled data.

The main methods used in unsupervised learning are : 
- Pricipal Component Analysis
- Cluster Analysis


### Reinforcement Learning
Straight copied from Wikipedia :
`
Reinforcement learning differs from supervised learning in not needing labelled input/output pairs be presented, and in not needing sub-optimal actions to be explicitly corrected. Instead the focus is on finding a balance between exploration (of uncharted territory) and exploitation (of current knowledge).
`


