# Transformer-Spam-Classification

## Description

Training a Transformer model to discriminate spam emails from legitimate ones.

## Overview  

An good example of a Transformer model at work, applied to the classification of spam emails as outlined in Google's paper [Attention Is All You Need](https://doi.org/10.48550/arXiv.1706.03762) (Vaswan, et al., 2017).

## Methodology

A Transformer model is constructed and trained (from scratch!) against 3000 emails from the [Email Spam](https://www.kaggle.com/datasets/veleon/ham-and-spam-dataset) dataset from Kaggle. As usual, a portion of the dataset is used for training, validation and testing.

## Evaluation

Standard statistical methods are used to evaluate the performance of the model against previously unseen emails.

## Outcome

The trained model achieved a 99% prediction accuracy against the test data set.
