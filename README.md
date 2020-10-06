# Word-Embeddings (Greek Language)
The size of the corpus that I used to training the word embeddings is around 16Gb and consists of different news articles. 

# Word2Vec
Python implementation of Word2Vec with Gensim. The parameters of the Word2Vec model that training are:
* size = 250
* window = 5
* min count = 50
* sg = 0 (CBOW)
* iter = 20

# FastText
Python implementation of FastText with Gensim. The parameters of the FastText model that training are:
* size = 250
* window = 5
* min count = 10
* sg = 0 (CBOW)
* iter = 20
* hs = 1 (hierarchical softmax)
* ngrams = 1

