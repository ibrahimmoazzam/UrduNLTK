# UrduNLTK

This repository contains Natural Language Processing (NLP) code for Urdu language that is meant to be contributed to the Natural Language Toolkit (NLTK) library.

## Getting Started

To use this code, you must have Python installed on your system along with the NLTK library. You can install NLTK by running the following command in your terminal or command prompt:

```python
pip install nltk
```

Once you have installed NLTK, you can clone this repository to your local machine using the following command:

```python
git clone https://github.com/ibrahimmoazzam/UrduNLTK
```

## Features

This repository contains the following NLP features for Urdu language:

- Tokenization: splitting text into individual words or tokens
- Part-of-speech (POS) tagging: labeling each word with its part of speech
- Stemming: reducing words to their base or root form
- Stop word removal: removing commonly used words that do not carry significant meaning

## Usage

To use the NLP features in your Python code, you must first import the necessary modules from NLTK and the urdu_nlp module in this repository. Here is an example:

```python
import nltk
from UrduNLTK import tokenizer, pos_tagger, stemmer, stopword_remover

text = "میں نے اپنا کام کر دیا"
tokens = tokenizer.tokenize(text)
pos_tags = pos_tagger.tag(tokens)
stemmed_tokens = [stemmer.stem(token) for token in tokens]
filtered_tokens = stopword_remover.remove(tokens)

print(tokens)
print(pos_tags)
print(stemmed_tokens)
print(filtered_tokens)
```

## Contribution

If you would like to contribute to this repository, please fork it and create a new branch for your changes. Once you have made your changes, create a pull request and describe the changes you have made and why they are necessary.
