<!-- Add banner here -->
<img src="img/banner.png" width="60%" height="5%">

# SENTENCE TO SENTENCE SEMANTIC SIMILARITY
<!-- Add buttons here -->
![GitHub last commit](https://img.shields.io/github/last-commit/bilalsp/S2S_Similarity_Model)
![GitHub pull requests](https://img.shields.io/github/issues-pr/bilalsp/S2S_Similarity_Model)
![GitHub issues](https://img.shields.io/github/issues-raw/bilalsp/S2S_Similarity_Model)
![GitHub stars](https://img.shields.io/github/stars/bilalsp/S2S_Similarity_Model)

<!-- Describe your project in brief -->
In this project,  we propose and implement the NLP model to compute the 
semantic similarity between two english sentences/questions using the Support Vector Machine(SVM).

**Full documentation is available inside "/docs" directory.**

# Table of contents
- [Description](#Abstract)
- [Results](#Results)
- [Conclusion](#Conclusion)

## Abstract
There are many methods available to compare words based on the context and the meaning, which convert the word into a representation in an n-dimensional vector space which is referred to as word embedding. Some of the methods are word2vec invented by Tomas Mikolov at Google, Glove from Stanford, and fastTest from Facebook. But, extending the notion of word similarity to complete sentence semantic similarity is one of the toughest problems in the Natural Language Processing(NLP). In this project, we build the system to compute the semantic similarity between two english sentences/questions using the Support Vector Machine(SVM). We consider the multiple similarities like literal similarity, shallow syntactic similarity, and latent semantic similarity as explanatory variables to predict the semantic similarity between two sentences. Our system predicts whether two sentences are duplicate or not based on the intent of the sentences.


## Dataset
We use `Quora Question Pairs` dataset to train our similarity model.

Source: [Quora Dataset](https://www.kaggle.com/c/quora-question-pairs)


## Results
<img src="img/ROC.JPG" width="40%" height="5%">


## Conclusion
In this project, we proposed and implemented the NLP model to compute the 
semantic similarity between two english sentences/questions using the Support Vector Machine(SVM).