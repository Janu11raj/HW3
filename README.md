# HW3
# Project Overview
This project implements a Question Answering (QA) system utilizing the BERT (Bidirectional Encoder Representations from Transformers) model. The aim is to accurately answer questions based on a given context by leveraging the capabilities of BERT to understand language nuances and semantics.

## Features
Model Training: Fine-tune the BERT model on a dataset containing questions and their corresponding answers.
Performance Evaluation: Assess the model's performance using the F1 score metric across different test datasets.
Flexible Input: Handle multiple datasets to evaluate the model's robustness.
Visualization: Display training loss history and performance metrics to track the model's learning process.

## Requirements
The following installed in your environment:
Python 3.x
PyTorch
Transformers
NumPy
Matplotlib
tqdm
## Dataset
The datasets used for training and testing in this project are:

spoken_train-v1.1.json: Contains training data with context, questions, and answers.
spoken_test-v1.1.json: Contains test data for evaluation.
Additional datasets for WER44 and WER54 variations.
