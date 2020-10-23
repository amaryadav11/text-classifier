# Problem statement #
Given a new document, we want to assign it to one of fixed categories.This is multi-class text classification problem.
>>
The problem is supervised text classification problem, and our goal is to investigate which supervised machine learning methods are best suited to solve it.

## Extracting words as numerical feature vectors ##
>>
The classifiers and learning algorithms can not directly process the text documents in their original form, as most of them expect numerical feature vectors with a fixed size rather than the raw text documents with variable length. Therefore, during the preprocessing step, the texts are converted to a numerical vector representation.

## Techniques for extracting features from text ##

1. Bag of words
2. Term Frequency, Inverse Document Frequency, abbreviated to tf-idf
3. Word2vec

## Build an train the model ##
>>
After all the above data transformation, now that we have all the features and labels, it is time to train the classifiers. There are a number of algorithms we can use for this type of problem.

1.Naive Bayes Classifier
2.Support Vector Machine Classifier
3.Decision Tree Classifier
4.Random Forest Classifier
5.etc...

# How to install and setup workspace ##
For Windows OS
1. Downlad and install Anaconda from https://docs.anaconda.com/anaconda/install/windows/
2. Install JupyterLab from https://jupyter.org/install
Run Jupyter Notebook
3.jupyter-lab .

To install python packages we can use pip or conda package manager

Python packages used
1. sklearn
2. numpy
3. pandas
4. gensim
5. nltk
6. joblib
7. matplotlib
8. re