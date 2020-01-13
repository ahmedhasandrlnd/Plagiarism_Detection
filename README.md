# Plagiarism_Detection

## Project Overview
In this project, we'll be building a plagiarism detector that examines a text file and performs binary classification; labeling that file as either plagiarized or not, depending on how similar that text file is to a provided source text.

This project will be broken down into three main notebooks:

## Notebook 1: Data Exploration
	1. Load in the corpus of plagiarism text data.
	1. Explore the existing data features and the data distribution.
	1. This first notebook is not required in your final project submission.

## Notebook 2: Feature Engineering
	1. Clean and pre-process the text data.
	1. Define features for comparing the similarity of an answer text and a source text, and extract similarity features.
	1. Select "good" features, by analyzing the correlations between different features.
	1. Create train/test .csv files that hold the relevant features and class labels for train/test data points.

## Notebook 3: Train and Deploy Your Model in SageMaker
	1. Upload your train/test feature data to S3.
	1. Define a binary classification model and a training script.
	1. Train your model and deploy it using SageMaker.
	1. Evaluate your deployed classifier.


