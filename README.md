# Sentiment Analysis of Russian Literary Classics

This project contains a Jupyter Notebook that performs sentiment analysis on classical Russian literature using a neural network. The main goal is to explore the emotional tone of the texts and identify unique sentiment features of these works.

### Repository Contents

Sentiment_Analysis.ipynb — The main notebook with steps for preprocessing, model configuration, and analysis.
Sample Text Files — Input files with excerpts from Russian literary classics (if included).
README — Description of the repository.

### Key Features

Data Preprocessing:
Text tokenization using the NLTK library.
Lemmatization of words via the pymorphy2 library.
Removal of stop words and unnecessary symbols.

### Neural Network Model:

Transformer-based model (BERT) for sentiment analysis.
Implemented using the transformers and torch libraries.

### Data Visualization:

Sentiment distribution plots using Matplotlib and Seaborn.

### Google Drive Integration:

Automatic loading of .txt files with texts from Google Drive.

### Requirements
Python 3.8 or higher.
Required libraries:
NLTK
PyMorphy2
Transformers
Torch
Pandas, NumPy, Matplotlib, Seaborn

### Results

Sentiment scores for each text.
Graphical representation of results, reflecting the emotional tone of the works.
