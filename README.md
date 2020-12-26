# Word-Embeddings (Greek Language)
The size of the corpus that I used to training the word embeddings is around 16Gb and consists of different news articles. You can download [Word2Vec embeddings](https://drive.google.com/drive/folders/1lR3WAvRH3zFEb2RtWVfPgEOwgaTM4qqM?usp=sharing) and [FastText embeddings](https://drive.google.com/drive/folders/10hQrUQ7J6kZq4MiQ3oWx7KGl6yBmu8WY?usp=sharing). 

# Word2Vec
Python implementation of Word2Vec with Gensim. The parameters of the Word2Vec model that trained are:
* size = 250
* window = 5
* min count = 10
* sg = 0 (CBOW)
* iter = 20

# FastText
Python implementation of FastText with Gensim. The parameters of the FastText model that trained are:
* size = 250
* window = 5
* min count = 10
* sg = 0 (CBOW)
* iter = 20
* hs = 1 (hierarchical softmax)
* ngrams = 1

