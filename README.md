# product-recommender-system

## Analyzing Iterative SVD algorithms for Large Scale Recommendation Systems

Recommender systems are generally used to recommend products to the user based on the
previous purchases made. We are trying to forecast the opinion the users will have on the
dissimilar substance and be able to recommend the finest product to each user. It is very
useful for both the customers and the sellers. For the customers, recommender systems will
help them to find the products which they are interested in and for the sellers, recommender
systems will improve the loyalty of their customers by enhancing the user experience and
further converting more browsers to consumers. By using Singular Value Decomposition
(SVD) we discover the relationships between the products which are in turn useful to
recommending products to users.

### Methodology 

- Data collection and preprocessing
- Converting the huge data matrix into smaller matrices using SVD’s
- Power Iteration Method will give the largest eigenvalues of the data matrix
- Lanczos Bidiagonalization Iteration will give the important eigenvalues of the data matrix
- Building a Recommendation model using the important data
- Giving recommendations to the user
