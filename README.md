# Spam Classifier

## What It Does: 
<p align="center">
  <br>
  <img src="https://github.com/ShubhamPy/Spam-Classifier/blob/master/Screenshots/Text%20Classification.png">
</p>


## How It Does:
Extract the text and the target class from the dataset. Extract the features of the test using TF-IDF vectorizer for the Input features.Split the skewed data into shuffled sets using stratified shuffle split in sklearn library. Use standard classifiers to classify the data into spam or ham.
<p align="center">
  <br>
  <img src="https://github.com/ShubhamPy/Spam-Classifier/blob/master/Screenshots/modelLearning.png">
</p>


## Dataset:
The SMS/Email Spam Collection is a set of SMS tagged messages that have been collected for SMS/Email Spam research. It contains one set of SMS messages in English of 5,567 messages, tagged according being ham (legitimate) or spam.

> You can collect raw dataset from [here](https://raw.githubusercontent.com/ShubhamPy/Spam-Classifier/master/spam.tsv).

The files contain one message per line. Each line is composed by two columns:
- `Class`- contains the label (ham or spam) 
- `Message` - contains the raw text.

## ModelPipeline:
<p align="center">
  <br>
  <img src="https://github.com/ShubhamPy/Spam-Classifier/blob/master/Screenshots/modelLayout.jpg">
</p>
