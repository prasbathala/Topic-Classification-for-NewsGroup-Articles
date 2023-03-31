# Topic-Classification-for-NewsGroup-Articles

This repository contains the implementation of classifier to classify the newspaper group. A lot of concepts were inspired from the book: [Machine Learning Techniques for Text, By Nikos Tsourakis](https://www.packtpub.com/product/machine-learning-techniques-for-text/9781803242385).

In this project, I have implemented techniques like PCA, LDA for reducing the dimensions. The classifier was built on Random Forest, K-nearest neighbours. With Random Forest, the accuracy was around 90%. 

Some Interesting observations from the data:
  1. KNN performance with Metadata: Accuracy - 90%
  2. KNN Performance without Metadata: Accuracy - 20% (lower than the baseline model ZeroR)
  3. RF without Metadata: 80%
  4. RF after reducing the dimensions using PCA: 89%
  5. KNN after reducing the dimensions using PCA: 89% (The wierd thing is that, without metadata, with tfidf vectorizer the model was able to achieve only 20% accuracy, but with 200 prinicpal components considered, the model was able to achieve 89% accuracy)
  
 
 The repository consists of a python notebook, where I have gone through the detailed analysis of the data and have shown how one model performed better than the other.
  
 
