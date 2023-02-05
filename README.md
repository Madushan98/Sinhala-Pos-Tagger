# Sinhala Part of Speach Tagger 

### Description
A Part of Speech (POS) Tagger is a tool that automatically tags words in a text corpus as a specific part of speech such as noun, verb, adjective, etc. This tool is useful for many Natural Language Processing (NLP) tasks such as text classification, text summarization, and sentiment analysis.

###  Methodology
The Sinhala Part of Speech Tagger uses a statistical approach based on the Hidden Markov Model (HMM). The HMM is a generative probabilistic model that can be used to predict the likelihood of a sequence of words in a text. In this case, the model predicts the most likely part of speech for each word in a sentence.

The HMM requires a large corpus of annotated text data to train the model. The Sinhala Part of Speech Tagger uses the Sinhala Treebank corpus, which is a treebank of Sinhala sentences manually annotated with part of speech tags. The model is trained using the Viterbi algorithm, which computes the most probable sequence of hidden states (part of speech tags) for a given sequence of observations (words).


#### Requirements

#### Dependencies
There are a number of third-party dependencies used in the project. Browse the Maven pom.xml file for details of libraries and versions used.

#### Building the project
You will need:

- Python 3.3+
- NLTK
- jupyter notebook
