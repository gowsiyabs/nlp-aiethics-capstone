# nlp-aiethics-capstone

#### This is a capstone project for my Master's in Analytics with Georgia Tech - 2021
Here is an outline of my approach to Challenge #1 i.e., implement and compare algorithms for clustering social
media posts and comments into semantic categories. Twitter data for analysis was provided by the Piper team. 
A 3-step process was used to achieve the desired results, the steps are:

    1. Tweets will be cleaned and pre-processed.
    2. Identify semantic relationships using Lemmatization, Tokenization, named entity recognition 
    and sentiment analysis.
    3. Apply clustering algorithms. As data is unlabeled tweets, we will use unsupervised 
    ML techniquessuch as Latent Dirichlet Allocation (LDA) Topic Modeling, Non-negative 
    Matrix Factorization (NMF) Topic Modeling, and K-Means clustering.

#### Structure of the project code
1. ```analyze_tweets_and_cluster_toy_dataset.ipynb``` - use this with ``` c1_toy_dataset.csv```
2. ```analyze_tweets_and_cluster_large_dataset.ipynb``` - with large dataset and data cannot be shared here

Note: There seem to be an issue with importing seaborn within my Jupyter lab however it works fine in Google colab.
