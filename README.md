# Toxic Comment Classification
This project aims to build a machine learning model that can identify and classify toxic comments on online platforms. A toxic comment is defined as a rude, disrespectful, or unreasonable comment that is likely to make someone leave a discussion or give up on sharing their perspective. Toxic comments can have various subtypes, such as severe toxic, obscene, threat, insult, and identity hate.
# Dataset
The dataset used for training and evaluation is the Toxic Comment Classification Dataset from Kaggle. It contains various comments labeled with their toxicity status.
You can download the dataset from the following link: https://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data?select=train.csv.zip .
# Model
The model architecture is based on a deep neural network using TensorFlow. It employs an embedding layer followed by LSTM layers to capture sequential patterns in the text data. The model is trained to classify comments into one of the toxicity categories
# Usage
To use the model, you need to install the following dependencies:
Python 
Tansorflow
scikit-learn
Pandas
Numpy
