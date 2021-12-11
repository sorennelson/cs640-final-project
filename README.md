# CS640 Project-COVID-19 Instagram posts emotion detection in relation to images of East Asian people + Ethnicity Detection

## Team members

 Qingyang Xu, Ge Gao, Hengwei Wang, Soren Nelson, Rishab Nayak

## Project Overview and Goal

This project is COVID-19 Instagram posts emotion detection (anger, fear, joy, and sadness) in relation to images of East Asian people. The basic task is to apply an emotion detection model trained on twitter dataset to instagram posts and examine the relation between emotion and the existence of East Asian people. The bonus task is to build a model for detecting whether there is an Asian person in the instagram posts images.

## Dependencies

Python 3.8

Jupyter notebook

Pytorch 1.0+

GPU recommended

## How it Works

The project includes:

Data loading

Feature engineering/Preprocessing

Model definition

Model training

Performance evaluation

Emotion predicting

## How to Run the Project

**data folder**: 

twitter folder includes 4 files for anger, fear, joy, and sadness emotion classification;

instagram_data.csv/xlsx is the test data for basic emotion detection task
            
images folder includes images data for bonus task
            
processed_instagram_data.csv is the labelled image data
            
**plots folder**: loss-epoch and accuracy-epoch plots for twitter data(training data in emotion detection task)

**classifier.ipynb**: notebook for emotion detection task: classifier notebook in master branch contains the best model we have; we created 'extra-models' branch and included our attempts with other models in the classifier.

**ethnicity_recognition.ipynb**: notebook for ethnicity detection task

instagram_labels.txt: a guide provided to understand features in instagram_data.csv/xlsx

**final_instagram_predictions.txt**: classification result based on our best model for emotion detection task. Each line contains the dataset index of the prediction and the emotion.

