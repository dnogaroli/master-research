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


## Screenshots

Timeline of the topics identified by the LDA model and their popularity in parliament.
![Evolution and popularity of Amazon rainforest-related topics in Brazil's parliament over time.](https://i.postimg.cc/pXLStGDd/yearly-average.jpg)

Map of all the parliamentary discourses on Amazon rainforest-related from 2000 to 2021.
![t-SNE clustering of LDA topics in discourses on the Amazon rainforest in Brazil's parliament from 2000 to 2021.](https://i.postimg.cc/zXDBWggQ/amazon-map.jpg)

