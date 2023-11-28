# Word-Embeddings (Greek Language)
The size of the corpus that I used to training the word embeddings is around 16Gb and consists of different news articles. You can download [Word2Vec embeddings](https://drive.google.com/drive/folders/1lR3WAvRH3zFEb2RtWVfPgEOwgaTM4qqM?usp=sharing) and [FastText embeddings](https://drive.google.com/file/d/1N-yEgXdWKNZii40wYo6vJVvVEzd3jSxM/view?usp=drive_link)). 

Also you can download a tweets pre annotated dataset for sentiment analysis for modern Greek. The dataset consists of 3 classes: positive, negative and neutral.

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

