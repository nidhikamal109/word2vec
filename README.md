# word2vec
It is a word embedding technique used in natural language processing (NLP) . Word2vec provides prediction based word embeddings. 
It uses three layers neural network (deep learning model) for predicting the vector of a word given its context or vice versa. 
There are two types of techniques available in word2vec -
1. CBOW (continuos bag of words) - it predicts the probability of a word given a context of a word(s) .
2. Skip gram model - it predicts the context for a given word . 

The respective notebooks implement the above two techniques . the python code explains the working of the neural network in cbow and skip gram . The text data used for generating the word embeddings is taken from the nltk's bible corpus .
