# topics_themes
Figuring out what topics and themes are emerging based on conferences and user searches

## Python Modules Needed
python 2.7.12

The following was installed with pip:

pandas (because you always need pandas)

nltk (with the stop words corpus. After installing nltk, >> import nltk, >> nltk.download()

This opens a gui. Go to 'Corpora' and select 'stopwords'. Then Download. Done.)

gensim (needs scipy, which needed brew install gcc to work)

pattern (for gensim)

pyLDAvis (for visualizing the topics)

pyenchant (a dictionary for separting words from non-words)
