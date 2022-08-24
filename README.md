# NLP-On-Plagiarism-Detection

# Project Overview
In this project, you will be tasked with building a plagiarism detector that examines a text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar the text file is to a provided source text.

# Defining Features
One of the ways you might go about detecting plagiarism, is by computing similarity features that measure how similar a given text file is as compared to an original source text. You can develop as many features as you want and are required to define a couple as outlined in this paper (which is also linked in the Lesson Resources tab. In this paper, researchers created features called containment and longest common subsequence.

In the next few sections, which explain how these features are calculated, I'll refer to a submitted text file (the one we want to label as plagiarized or not) as a Student Answer Text and an original, wikipedia source file (that we want to compare that answer to) as the Wikipedia Source Text.

You'll be defining a few different similarity features to compare the two texts. Once you've extracted relevant features, it will be up to you to explore different classification models and decide on a model that gives you the best performance on a test dataset.

This project will be broken down into three main notebooks:

## Notebook 1: Data Exploration

- Load in the corpus of plagiarism text data.
- Explore the existing data features and the data distribution.
- This first notebook is not required in your final project submission.

## Notebook 2: Feature Engineering

- Clean and pre-process the text data.
- Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
- Select "good" features, by analyzing the correlations between different features.
- Create train/test .csv files that hold the relevant features and class labels for train/test data points.

## Notebook 3: Train and Deploy Your Model in SageMaker

- Upload your train/test feature data to S3.
- Define a binary classification model and a training script.
- Train your model and deploy it using SageMaker.
- Evaluate your deployed classifier.

