# Emotion Extraction and Classification from Twitter Text using Deep Learning

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Dataset](#dataset)
* [Models](#models)
* [Result](#result)
* [Conclusion](#conclusion)

## General info 
Emotion is one of the basic instincts of a human being. Emotion detection plays a vital role in the field of textual analysis. At present, people’s expressions and emotional states have turned into the leading topic for research works.In this project, Our primary goal is to detect human’s emotion from text input through some Deep Learning Model.
	
## Technologies
Project is created with:
* **Google Colab**

Language used:
* **Python**

Library used:
* **Pytorch**
* **NLTK**
* **Tensorflow**
* **sklearn**

Word Emebedding:
* **[GloVe](https://nlp.stanford.edu/projects/glove/)**
	
## Dataset
Here tweet emotions from SemEval-2018 Affect in Tweets Distant Supervision Corpus (AIT-2018 Dataset) is used.This dataset has two columns content and sentiment. It has 20000 unique text classified with 6 emotions such as anger, love, surprise, fear, joy, sadness. This dataset contains lots of emotions but they mainly clustered those emotions into 4 basic emotions such as anger, fear, joy, sadness.

## Models
* Convolutional Neural Network (CNN)
* Bidirectional Long Short Term Memory (Bi-LSTM)

## Result
Accuracy of the two models - Convolutional Neural Network (CNN) and Bidirectional Long Short Term Memory (Bi-LSTM)
are `90.00%` and `92.33%` respectively.

## Conclusion 
In this project, we have used ”tweet emotions from
SemEval-2018 Affect in Tweets Distant Supervision Corpus
(AIT-2018 Dataset)”. As it’s a noisy dataset, first we had
to do the preprocessing such as punctuation remove and
converted emojis into texts, tokenization, contraction. Then
we have implemented two models and compared them. After
comparing them, we observed that Bi-directional long short
term memory model gave the highest accuracy which is
**92.33%**. After completion of our project, we observed that
our project can detect emotions from texts.



