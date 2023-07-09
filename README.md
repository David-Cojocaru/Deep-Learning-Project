# Deep-Learning-Project

<h1 align="center">
  <br>
Amazon Book User Review Score Predictor
  <br>
  <img src="https://raw.githubusercontent.com/David-Cojocaru/Deep-Learning-Project/assets/AmazonBookReviews.png" height="200">
</h1>
  <p align="center">
    David Cojocaru</a> •
    Ori Hagler</a>
  </p>

## Overview

- Final Project of the Technion ECE 046211 - Deep Learning Course
- Spring 2023 Semester
- Authors: David Cojocaru, Ori Hagler

## Description

We used the Amazon Book Reviews dataset containing 3M user reviews of market-available books to make a predictor for the user score assigned to the fitting review.
As a base for this project, we used the BertForSequenceClassification pre-trained model and fine-tuned it to fit a 1-5 score predictor, similar to non-binary sentiment classification.
We integrated transfer learning on a transformer model while using techniques like pruning of the model, AMP, and optimal hyperparameter search using Optuna.

## Preparing The Nessecery Files
To run this notebook, you first need to download a pre-trained model and a .json file.
Once you have all the files, you may want to configure the file paths to match those written in the notebook

### Pre-Trained Model Checkpoints
You can download one of the checkpoints from here:

- Pre-Trained BERT classifier model: https://drive.google.com/file/d/1dsr0WPp24lZe9ZiVba35AXrSCQPayiL5/view?usp=drive_link
- Pre-Trained Fine-Tuned classifier model: https://drive.google.com/file/d/1S7ym7tiG9lTkD_eRb_I3kJn2OWhaLlNu/view?usp=drive_link

The first option is the model we used as a base for training, and the second is the model after fine-tuning done during the training phase (about 100k samples)

### Kaggle json file
To access the dataset, instead of downloading 3M samples, we source our dataset from Kaggle.
To do that, you are required to get a kaggle.json file, here is how to do it:

- Go to your Kaggle account, Scroll to API section and Click Expire API Token to remove previous tokens
- Click on Create New API Token - It will download kaggle.json file on your machine.
