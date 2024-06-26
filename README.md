# Music Genre Classification

## CODE AUTHORS
Dhruv Doshi

Arinjay Jain

Santosh Saranyan

## About the project:
This project focuses on the implementation and evaluation of various models, including Naïve Bayes as the baseline, Multiclass logistic regression, long short-term memory (LSTM), and LinearSVM, to classify songs into their respective genres based on the lyrics of each song. The dataset comprises over 138,000 English songs from various genres merged from 2 sources. It implements 2 word embedding techniques, Word2Vec and GLoVe, after preprocessing and cleaning the data. The performances of different models and embedding techniques are evaluated by calculating the accuracy, precision, recall, and F1 score. The results of this study can be used by music industry professionals to gain insights about the popularity and trends of different music genres and make data-driven decisions about music production and marketing. The project concludes by discussing the differences between the results obtained from each model and suggesting the most appropriate model for genre classification based on a song lyric task.

## FILES IN REPOSITORY
**data**: https://www.dropbox.com/s/90i3kyd6z2e3s52/data.zip?dl=0 folder containing all necessary datasets and text files to run the project. This file has been compressed as a zip file. Extract before use.

**data_merging**: This file contains python code to get information about a song’s genre from last.fm’s API and combine it with our dataset.

**svm_model_implementation**: This is a notebook file consisting of the implementation steps for preparing the data, training the SVM model, tuning it, and evaluating the model performance on test data using Word2Vec embeddings and GloVe embeddings each.

**preprocessing_lyrics_dd_final**: This is a notebook file consisting of the implementation steps for pre-processing the data like case folding, removal of stop words, lemmatization, etc. Finally, it saves the modified dataset as a csv file.

**GNB and Logistic Regression**: This notebook has implementation of sklearn Gaussian Naive Bayes and Logistic Regression classifiers as well as a PyTorch implementation of a Logistic Regression classifier. Experiments with different embeddings and hyper parameters are performed and their performance is calculated. To run thai file, install the libraries imported at the top of the notebook and run all cells in order.

**Genre_Reduction**: This is a notebook file that normalizes the names of the genres and combines various sub-genres into one. It filters out genres that have fewer songs and visualizes a word cloud for the most frequent words for each genre.

**Word_Embeddings**: This is a notebook file that trains and creates Word2Vec embeddings on the corpus. A word similarity plot is visualized for the Word2Vec and pre-trained GloVe embeddings with the help of t-SNE to reduce dimensions.

**LSTM_Model**: This is a notebook file that builds, trains and evaluates an LSTM model with PyTorch. Two models are trained, one for each word embedding.

## SOURCE FOR THE DATASET
https://www.kaggle.com/datasets/neisse/scrapped-lyrics-from-6-genres 
