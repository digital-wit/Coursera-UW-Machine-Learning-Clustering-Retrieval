# Coursera UW Machine Learning Clustering & Retrieval

- Week 1 Intro
  - Welcome and introduction to clustering and retrieval tasks
  - Course overview
  - Module-by-module topics covered
  - Assumed background

- Week 2 Nearest Neighbor Search
  - Introduction to nearest neighbor search and algorithms
    - Retrieval as k-nearest neighbor search
    - 1-NN algorithm
    - k-NN algorithm
  - The importance of data representations and distance metrics
    - Document representation
    - Distance metrics: Euclidean and scaled Euclidean
    - Writing (scaled) Euclidean distance using (weighted) inner products
    - Distance metrics: Cosine similarity
    - To normalize or not and other distance considerations
  - Scaling up k-NN search using KD-trees
    - Complexity of brute force search
    - KD-tree representation
    - NN search with KD-trees
    - Complexity of NN search with KD-trees
    - Visualizing scaling behavior of KD-trees
    - Approximate k-NN search using KD-trees
    - (OPTIONAL) A worked-out example for KD-trees
  - Locality sensitive hashing for approximate NN search
    - Limitations of KD-trees
    - LSH as an alternative to KD-trees
    - Using random lines to partition points
    - Defining more bins
    - Searching neighboring bins
    - LSH in higher dimensions
    - (OPTIONAL) Improving efficiency through multiple tables
  - Summarizing nearest neighbor search
    - A brief recap
    
- Week 3 Clustering with k-means
  - Introduction to clustering
    - The goal of clustering
    - An unsupervised task
    - Hope for unsupervised learning, and some challenge cases
  - Clustering via k-means
    - The k-means algorithm
    - k-means as coordinate descent
    - Smart initialization via k-means++
    - Assessing the quality and choosing the number of clusters
  - MapReduce for scaling k-means
    - Motivating MapReduce
    - The general MapReduce abstraction
    - MapReduce execution overview and combiners
    - MapReduce for k-means
  - Summarizing clustering with k-means
    - Other applications of clustering
    - A brief recap

- Week 4 Mixture Models: Model-Based Clustering
  - Motivating and setting the foundation for mixture models
    - Slides presented in this module
    - Motiving probabilistic clustering models
    - Aggregating over unknown classes in an image dataset
    - Univariate Gaussian distributions
    - Bivariate and multivariate Gaussians
  - Mixtures of Gaussians for clustering
    - Mixture of Gaussians
    - Interpreting the mixture of Gaussian terms
    - Scaling mixtures of Gaussians for document clustering
  - Expectation Maximization (EM) building blocks
    - Computing soft assignments from known cluster parameters
    - (OPTIONAL) Responsibilities as Bayes' rule
    - Estimating cluster parameters from known cluster assignments
    - Estimating cluster parameters from soft assignments
  - The EM algorithm
    - EM iterates in equations and pictures
    - Convergence, initialization, and overfitting of EM
    - Relationship to k-means
    - (OPTIONAL) A worked-out example for EM

- Week 5 Latent Dirichlet Allocation: Mixed Membership Modeling
  - Introduction to latent Dirichlet allocation
    - Slides presented in this module
    - Mixed membership models for documents
    - An alternative document clustering model
    - Components of latent Dirichlet allocation model
    - Goal of LDA inference
  - Bayesian inference via Gibbs sampling
    - The need for Bayesian inference
    - Gibbs sampling from 10,000 feet
    - A standard Gibbs sampler for LDA
  - Collapsed Gibbs sampling for LDA
    - What is collapsed Gibbs sampling?
    - A worked example for LDA: Initial setup
    - A worked example for LDA: Deriving the resampling distribution
    - Using the output of collapsed Gibbs sampling
    
- Week 6 Hierarchical Clustering & Closing Remarks
  - What we've learned
    - Module 1 recap
    - Module 2 recap
    - Module 3 recap
    - Module 4 recap
  - Hierarchical clustering and clustering for time series segmentation
    - Why hierarchical clustering?
    - Divisive clustering
    - Agglomerative clustering
    - The dendrogram
    - Agglomerative clustering details
    - Hidden Markov models
  - Summary and what's ahead in the specialization
    - What we didn't cover
    - Thank you!