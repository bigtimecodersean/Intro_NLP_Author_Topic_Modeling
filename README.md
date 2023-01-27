# Intro_NLP_Author_Topic_Modeling

A project to introduce myself to NLP: a very basic attempt at topic modelling this Spooky Author dataset: https://www.kaggle.com/c/spooky-author-identification

For this project, I was more interested in visualizing salient terms for each of the 3 authors in the dataset, than I was predicting which text was written by which author.  

Topic modelling is the process in which you try uncover abstract themes or "topics" based on the underlying documents and words in a corpus of text. 

I used the Latent Dirichlet Allocation (LDA) technique

**Outline:**
- Exploratory Data Analysis (EDA) and Wordclouds: Analyzing the data by generating simple statistics such word frequencies over the different authors as well as plotting some wordclouds (with image masks).

- Natural Language Processing (NLP) with NLTK (Natural Language Toolkit): Introducing basic text processing methods such as tokenizations, stop word removal, stemming and vectorizing text via term frequencies (TF) as well as the inverse document frequencies (TF-IDF)

- Topic Modelling with LDA 
