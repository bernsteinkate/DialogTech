# Tutorials
Install Python (version 3.6) using a Jupyter notebook.
You can either install it using Pip or Conda

http://jupyter.org/install
Open python interpreter by opening terminal and typing 'python'

INSTALLATION
------------
### Conda Install:

(Make sure you are in the root of your repository)

>>> conda create --name tutorial --file spec-file.txt 

>>> python -m ipykernel install --user --name tutorial --display-name "Python (tutorial)"

Change kernel to 'tutorial'

>>> pip install -r requirements.txt

### Pip install:

Create your own environment and activate it

>>> pip install -r requirements.txt

-change kernel to 'tutorial'

### Other installs:

Install Nltk and Stopwords:

>>> import nltk

>>> nltk.download()

A Gui box will pop up with different options for downloading stopwords
Install the 'popular' package for stopwords

Install spaCy english dictionary:

>>> python -m spacy.en.download

TUTORIALS
------------

Titanic_Markdown.ipynb :
The purpose of this tutorial is to be introduced to a Machine Learning binary classification problem. It practices aquiring and analyzing data, data visualization, wrangling data, and modeling and evaluating data.
This is the Jupyter notebook code for the Titanic Kaggle Problem
https://www.kaggle.com/c/titanic

Matplotlib_Markdown.ipynb :
The purpose of this tutorial is to provide smaller scale examples of data visualization in order to practice using the libraries matplotlib, pandas, numpy, and more. It also introduces getting data using Elasticsearch.
Useful links:
https://matplotlib.org/gallery/index.html

Bag_of_Words.ipynb :
The purpose of this tutorial is to become familiar with the Bag of Words model and have an introduction to modeling text. 
This includes the Jupyter notebook for part 1 of the Bag of Words Kaggle Problem
Useful links:
https://machinelearningmastery.com/gentle-introduction-bag-words-model/
https://www.kaggle.com/c/word2vec-nlp-tutorial#description

Topic_Modeling_Markdown.ipynb :
The purpose of this tutorial is to give a more in depth approach word processing, topic modeling, and cosine similarity.
Useful links:
https://medium.com/mlreview/topic-modeling-with-scikit-learn-e80d33668730

Nltk_Markdown.ipynb:
The purpose of this tutorial is to have practice using word processing library nltk and extract features from a corpus. It also introduces the similar library spaCy. 
Useful links:
http://www.nltk.org/book/
https://spacy.io/usage/linguistic-features

Voicemail_Markdown.ipynb:
The purpose of this tutorial is to practice building a simple binary classification model. While this tutorial is similar to the Titanic tutorial, it is more straightforward and introduces feature selection, basic machine learning models, and k fold cross validation.
Useful links:
https://medium.com/@sifium/machine-learning-types-of-classification-9497bd4f2e14
http://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.SelectKBest.html
https://machinelearningmastery.com/k-fold-cross-validation/

ElasticSearch_Markdown.ipynb:
This tutorial explains how to retreive data using the search engine ElasticSearch. It uses Topic_Modeling.ipynb as an example and teaches how to write a query, attend to date range requirements, create a dataframe, and store it to a csv for later use. 
Useful links:
https://www.elastic.co/guide/en/elasticsearch/reference/current/getting-started.html

Voicemail_elastic.ipynb:
This is another elasticsearch tutorial, and a quick demonstration of how the data is retreived for Voicemail_classification.ipynb. It shows the functions used to calculate the new feature 'switches', using scan and scroll on a large dataset, and merging two csv's together that have one shared feature. 
Useful links:
https://www.elastic.co/guide/en/elasticsearch/guide/1.x/scan-scroll.html


