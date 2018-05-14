# Machine Learning Cliff Notes

These Jupyter notebooks are my notes as I work through this stuff. I make no guarantee that these are correct. If you find an error or something that's unclear, please let me know. 

## Table of Contents

 - [Linear Regression](linear_regression.ipynb)
 - [Logistic Regression](logistic_regression.ipynb)
 - [Naive Bayes](naive_bayes.ipynb)
 - ~~[Desision Trees](desision_trees.ipynb)~~
 - [K-means](kmeans.ipynb)
 - ~~[Gaussian Mixture Models](gmm.ipynb)~~
 - ~~[Principle Component Analysis](pca.ipynb)~~
 - ~~[Neural Networks](neural_networks.ipynb)~~


## Outline

**For each ML model:**

Top-level
 - What is the high-level version, explain in layman's terms
 - What scenario should you use it in (classification vs regression, noisy data vs clean data)?
 - How does this deal with outliers? Skewed data?
 - What assumptions does the model make about the data? (Linear, etc)?
 - What types of features does the model use (continuous vs categorical)?
 - When does the model break/fail (adv & dis-advantages)?
 - use cases/alternatives when it breaks

A bit more detail:
 - How do you normalize the data for the model, if you need to?
 - How to initialize parameters at beginning (e.g. where to put centroid in KMeans)
 - What's the loss function used (if many, what are tradeoffs of each)?
 - What optimizers can you use here?
 - What's the complexity — runtime, parameters?
 - How does it scale with # of features or input data?
 
In-depth
 - probabilistic interpretation
 - Derive the math (only for a couple models)
 - Code up implementation (only for a couple models)

More on training the model (not model-specific, this should be common for most of the models):
 - How to deal with imbalanced data?
 - How well does it generalize to unseen data (over-fitting vs under-fitting)?
 - What if you have MANY more features than sample points? Vice versa? (A variation of the above over/under fitting)
 - How do you regularize the model? Tradeoffs?
 - How can you validate the model?
 - Does the model emphasize Type 1 or Type 2 errors?


## Great Resources

I borrow heavily from the resources below; this includes code snippets, figures, derivations, and explanations.

 - [Victor Lavrenko on youtube](https://www.youtube.com/channel/UCs7alOMRnxhzfKAJ4JjZ7Wg)
 - [lazy programmer classes on Udemy](https://www.udemy.com/user/lazy-programmer/)
 - [Neural networks and deep learning](http://neuralnetworksanddeeplearning.com)
 - [Neural networks, manifolds, and topology](http://colah.github.io/posts/2014-03-NN-Manifolds-Topology/)
 - [Scikit-Learn (SK-learn)](http://scikit-learn.org/stable/)
 - [41 Essential Machine Learning Interview Questions](https://www.springboard.com/blog/machine-learning-interview-questions/)
