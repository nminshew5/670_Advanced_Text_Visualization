# Advanced Text Visualization

The purpose of this tutorial is to demonstrate advanced visualization techniques for social media analytics and web mining concepts.

A common problem that data scientists run into is having trouble explaining their findings to those who are not familiar with analytics.
This is very important in the business environment, when the findings from data can help to drive decision making. It is vital for the data scientist to make his or her findings easily understandable and actionable. The solution to this problem is using visualization techniques that make understanding models, features, and findings easy and intuitive. Not only are visualizations useful for those who are not familiar with data science and analytics, they can also help even the most experienced data scientists better understand their work.

## Outline of Topics and Packages Covered
* Setup and Install Packages
  * Import Packages
* Basic Descriptive Text Analytics Visualization
  * Loading and preparing data
  * Matplot Visualization of Word Frequency
  * Seaborn Visualization of Word Frequency
* Scattertext for Descriptive Text Analytics
  * Data Processing Using Scattertext
  * Creating Corpus using scatter text and spaCY
  * Visualizing Terms and Associations with Scattertext
  * Topic Modeling Visualization with Scattertext and Empath
  * Text Classification Visualization with Scattertext and SKlearn
  * Sentiment Analysis and Visualization
  * Visualizing Sentiment with Semiotic Squares

# Package Installation and Prerequisites
*Note: Some of these packages may require Python 3.6 and will not work on python 2.7*
### Seaborn
Seaborn is a Python visualization library based on matplotlib. It provides a high-level interface for drawing attractive statistical graphics.
https://seaborn.pydata.org/
  ```
  pip install seaborn
  conda install seaborn
  ```
### Bokeh
Bokeh is a Python interactive visualization library that targets modern web browsers for presentation.
https://bokeh.pydata.org/en/latest/
```
pip install bokeh
conda install bokeh
```
### NLTK
Package for text analytics
```
pip install NLTK
```
### Scattertext
A tool for finding distinguishing terms in small-to-medium-sized corpora, and presenting them in a sexy, interactive scatter plot with non-overlapping term labels. Exploratory data analysis just got more fun.
https://github.com/JasonKessler/scattertext#installation
```
pip install scattertext
```
### We will also need some additional packages to use Scattertext:
#### SpaCY
https://spacy.io/usage/
```
conda install -c conda-forge spacy
pip install -U spacy
```
Now you need to download a language model. Make sure to run command promt as administrator
```
python -m spacy download en
```
#### Jieba
https://github.com/fxsjy/jieba
```
pip install jieba
```
#### Empath
https://github.com/Ejhfast/empath-client
Find out more here: https://arxiv.org/pdf/1602.06979.pdf
```
pip install empath
```
#### Gensim
https://radimrehurek.com/gensim/
```
conda install -c anaconda gensim
```
#### UMAP
https://github.com/lmcinnes/umap
```
pip install umap
```  

