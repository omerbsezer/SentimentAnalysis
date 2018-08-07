# Sentiment Analysis

Sentiment Analysis is an analysis of the sentence, text at the document that gives us the opinion of the writer. In this project, it will be implemented a model which inputs a sentence and finds the most appropriate emoji to be used with this sentence. Code is adapted from Andrew Ng's Course 'Sequential models'.

We have a tiny dataset (X, Y) where:

* X contains 127 sentences (strings)
* Y contains a integer label between 0 and 4 corresponding to an emoji for each sentence



Glove 50 dimension, 40000 words of dictionary file is used for word embeddings. It should be downloaded from  https://www.kaggle.com/watts2/glove6b50dtxt (file size = ~168MB))

* word_to_index: dictionary mapping from words to their indices in the vocabulary (400,001 words, with the valid indices ranging from 0 to 400,000)
* index_to_word: dictionary mapping from indices to their corresponding words in the vocabulary
* word_to_vec_map: dictionary mapping words to their GloVe vector representation.


LSTM structure is used for classification.