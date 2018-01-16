# Machine Learning

## Essential Algorithms

  - Decision Tree: A decision tree is a decision support tool that uses a tree-like graph or model of decisions and their possible consequences
  
  - Naive Bayes Classification: Naive Bayes classifiers are a family of simple probabilistic 
  classifiers based on applying Bayes' theorem with strong(naive) independence assumptions
  between the features.
  
  The freatured image is the euqation
  
  P(A|B) : posterior probability
  
  P(B|A) : likelihood
      
  P(A)   : class prior probability
      
  P(B)   : predictor prior probability
      
**P(A|B) P(B) = P(B|A) P(A)** 

  - Ordinary Least Squares Regression: applying least-suqare methond on linear regression
  
  - Logistic Regression: a powerful statistical way of modeling a bonomial outcome with
  one or more explanatory variables. It measures the relationship between categorical deoendent
  variable and one or more independent variables by estimating probabilities using a logistic
  function, which is the cumulative logistic distribution
  
  - Support Vector Machines: SVM is binary classification algorithm. Given a set of points of
  2 types in N dimensional place, SVM generates a (N-1) dimensional hyperplane to separate
  those points into 2 groups. Say you have some points of 2 types in a paper which are lieanly
  separable. SVM will find a straight line which separates those points into 2 types and
  situated as far as possible from all those points.
  
  - Ensemble Methods: Ensemble methods are learning algorithms that construct a set of classifiers 
  and then classify new data points by taking a weighted vote of their predictions. The original
  ensemble method is Bayesian averaging, but more recent algorithms include error-correcting 
  output coding, bagging and boosting.
  
  - Clustering Algorithms: clustering is the task of grouping a set of objects such that
  objects in the same group(cluster) are more similar to each other than to those in other
  groups.
  
  Several clustering algorithms
    - Centroid-based algorithms
    - Connectivity-based algorithms
    - Density-based algorithms
    - Probabilistic
    - Dimensionality Reduction
    - Neural Netword/Deep Learning
 
 - Principal Component Analysis: PCA is a statistical procedure that uses an orthogonal
 transfornation to convert a set of observations of possibly correlated variables into 
 a set of values of linearly uncorrelated variables called principal components.
 
 - Singular Value Decomposition: SVD is a factorization of a real comple matrix. For a 
 give _m_ x _n_ matrix M, there exists a decompostion such that M = U Sigma V where U and V
 are unitary matrices and Sigma is a diagonal matrix.
 
 - Independent Component Analysis: ICA is a statistical technique for revealing hidden 
 factors that underlie sets of random variables, measuremnts or signals. ICA defines a
 generative model for the observed multivariate data, whic is typically given as a large
 database of samples. In the model, the data variables are assumed to be linear mixtures
 of some unknown latent variables, and the mixing system is also unknown. The latent
 variables are assumed non-guassian and components of the observed data.
    

## Supervised Learning

    The algorithm consit of a target/outcome variable or dependent variable which is to be predicted from
    a given set of predictors (independent variables). Using these set of variables, we generate a function
    that map inputs to desired outputs. The traning process continues until the model achieves a desired level
    of accuracy on the traning data
    
    Example: - Regression
             - Decision Tree
             - Random Forest
             - KNN
             - Logistic Regression
             
             
             
## Unsupervised Learning

    this algorithm do not have any target or outcome variable to predict/estimate. It is used for
    clustering population in different groups, which is widely use dfor segmenting customers in
    different groups for specific intervention.
    
    Example: - Apriori algorithm
             - K-means
