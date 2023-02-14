# Capstone Project Fake News Detector

This Project was built and run using Amazon Sage maker.
The folder "data" contains the downloaded data files from Kaggle: https://www.kaggle.com/clmentbisaillon/fake-and-real-news-dataset


STEP 1. In the "Data Exploration and Visualization" Notebook, we are exploring and cleaning the data and then saving it to an s3 bucket.

STEP 2. In the "Model building, Training and Deployment" Notebook, we used Naive Bayes method resulting in a failed accuracy score.

STEP 3. In the "Text generating for RNN and Training"Notebook, using tokenized articles we were able to train a Bidirectional LSTM with a single sigmoid output, resulting  in a test accuracy score of 98%.

Important Files and Folders 

(source_train folder) - contains training scripts for Naive Bayes and LSTM methods.

(helper.py file) - contains several useful functions. 

(tokenizer.pkl file) - contains a pickled version of the fitted Keras used to preprocess data for the LSTM.

