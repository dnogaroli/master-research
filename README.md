# Exploring Brazil’s parliamentary discourses dynamics on the Amazon rainforest using Topic Modeling

This repo holds the script developed for the MA in Communication & Information Studies in Digital Humanities at the University of Groningen.

The research delves into parliamentary discourses' dynamics on the Amazon rainforest in Brazil over the first decades of the year 2000, incorporating information technology in humanities research.

## Roadmap

### `code` 

`amazon_keywords.ipynb`: filters discourses that contains keywords related to the Amazon rainforest.

`cleaning_discourses.ipynb`: removes noises at the beginning of the discourses. 

`pre-processing.ipynb`: clean the discourses and make it ready to feed data to the models.

`lda_tm.ipynb`: build LDA model.

`lda_dtm.ipynb`: build DTM based on the LDA model.

### `src` 

It contains the LDA topic model inputs: the dictionary and the corpus.

### `vis` 

LDAvis, and TM and DTM results in `.html`.
