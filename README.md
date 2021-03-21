# MetaDataSeachAndTag
MetaDataSeachAndTag is  part of search engine, which is a collection of documents converted to a machine-readable representation, and classified into broad topics. Imagine doing search on a small set of 1M documents. You might have 100K documents in *computer science* topic, 100K in the *animals* topic, another 100K in a *politics* topic, etc. When a user query  for computer topic  so that you only have to search through 100K documents rather than the whole 1M document collection.Also we are  suggesting the  classified topic which are not in existing in category

In this practical, we will use Wikipedia to create a small collection of documents on certain topics. We will convert those documents into vectors. And finally, we will test  whether a given user query is mapped to the correct topic in the collection.

below are the process followed to builed the project:
### Tranforming the data into features:
Convert our raw texts into sets of features. We will do this using a vocabulary of character ngrams.
### Feature selection
### Documention Information Retrieval using TF-IDF measure.
TF-IDF or ( Term Frequency(TF) — Inverse Dense Frequency(IDF) )is a technique which is used to find meaning of sentences consisting of words and cancels out the incapabilities of Bag of Words technique which is good for text classification or for helping a machine read words in numbers. However, it just blows up in your face when you ask it to understand the meaning of the sentence or the document.
###Text in Description is pre-processed by removing unwanted characters and words. 
#### Stop words are removed and all the words are lemmatized.Stop words are a set of commonly used words in a language. Examples of stop words in English are “a”, “the”, “is”, “are” and etc. The intuition behind using stop words is that, by removing low information words from text, we can focus on the important words instead.

### Lowercasing ALL your text data, although commonly overlooked, is one of the simplest and most effective form of text preprocessing.
### removed Punchuation 
### Created cosine similarity matrix
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
### c.Mapping queries to topics


# Referance Data
can be downloaded from https://ripsita-meta.herokuapp.com/api/v1/metatagger/refdata
