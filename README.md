# Machine Learning Cliff Notes

These Jupyter notebooks are my notes as I work through this stuff. I make no garentee that these are correct. If you find an error, or something that's unclear, please let me know. 

Table of Contents

 - [Linear Regression](linear_regression.ipynb)
 

These notes attempth to follow the Ashwin-Anitha framework:


**For each ML model:**

Top-level
 - What is the high level version, explain in layman's terms
 - What scenario should you use it in (classification vs regression, noisy data vs clean data)?
 - How does this deal with outliers? Skewed data?
 - What assumptions does the model make about the data? (Linear, etc)?
 - What types of features does the model use (continuous vs categorical)?
 - When does the model break / fail (adv & dis-advantages)?
 - use cases / alternatives when it breaks

A bit more detail:
 - How do you normalize the data for the model, if you need to?
 - How to initialize parameters at beginning (e.g. where to put centroid in KMeans)
 - What's the loss function used (if many, what are tradeoffs of each)?
 - What optimizers can you use here?
 - What's the complexity — runtime, parameters?
 - How does it scale with # of features or input data?
 
In-depth
 - probabilistic interpretation
 - Derive the math (only for a couple models)*
 - Code up implementation (only for a couple models)*

More on training the model (not model-specific, this should be common for most of the models):
 - How to deal with imbalanced data?
 - How well does it generalize to unseen data (over-fitting vs under-fitting)?
 - What if you have MANY more features than sample points? Vice versa? (A variation of the above over/under fitting)
 - How do you regularize the model? Tradeoffs?
 - How can you validate the model?
 - Does the model emphasize Type 1 or Type 2 errors?
