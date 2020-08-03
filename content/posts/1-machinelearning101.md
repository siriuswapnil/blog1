---
title: "#1 Machine Learning 101"
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

In a nutshell, classical programming allows us to formulate some rules, provide some input data and expect results from the computer. A simple example is an authentication system. We formulate rules to setup a database, check the presence of user's credentials in the database, and permit him access for the time.

On the other hand, there exist some problems that cannot be fixed using common programming techniques. These 'modern' problems, are somewhat are the foundations of field of Aritificial Intelligence.

A common example of this type of problem is the classification of cats from dogs. Both have similar features; two eyes, one nose, two ears( different kinds). Moreover, there might even be multiple cats or dogs in a given image. Hence, if we were to write conditionals to distinctively identify each of these features, it would take us thousands, if not millions of lines of code.

This is where machine learning comes in.
Here, we provide example data to the computer. For instance, we provide pictures of cats and dogs along with the labels (usually called a dataset) to a training algorithm or a *model*. So the machine using the algorithm *learns* whether it is a cat or a dog, and *predicts* the result.

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


## Reinforcement Learning
Straight copied from Wikipedia :
```
Reinforcement learning differs from supervised learning in not needing labelled input/output pairs be presented, and in not needing sub-optimal actions to be explicitly corrected. Instead the focus is on finding a balance between exploration (of uncharted territory) and exploitation (of current knowledge).
```


Tools for learning ML : Statistics and Probability


