# E-commerce-sentiment-analysis-using-ML

Unsupervised Learning algorithm is used to analyse unlabelled datasets. It's like having no teacher to guide you. Especially in cases where experts are unfamiliar with what to look for in 
data, algorithms such as these are helpful. These algorithms try to use techniques on the input data to mine for rules, detect patterns, and summarize and group the data points which help 
in deriving meaningful insights and describe the data better to the users.

Pre-processing:
1. Tokenization
2. Normalizing text
3. Removing punctuations
4. Non-alpha characters are removed

A technique known as clustering was used with the E-commerce dataset. Clustering, often known as grouping, is a technique for organizing data into groups of items that share similar features. This technique simplified data. We used this 
for data classification in this case, but can be used in numerous ways.

Python Gensim includes a Word2Vec toolbox. Natural language processing package Gensim helped us to extract features, semantics, and other information from the E-commerce dataset 
automatically.

The column "review text" is the attribute analysed from the E-commerce dataset. Word2vec is made up of two different learning models: CBOW and Skip gram. We are training the Ecommerce dataset using the Skip-gram model for this project. 
