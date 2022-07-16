## **Collaborative Filtering for Movie Ratings Prediction via Gaussian Mixtures**

* Built a Gaussian Mixture Model from scratch, using numpy and scipy, for collaborative filtering using a data matrix containing movie ratings in the
range 1-5, made by users on Netflix. 
* Any particular user rated only a small fraction of the movies so the data matrix was only partially filled. 
* Made BIC score plot to select number of clusters. 
* Then predicted all the remaining entries of the matrix using the model. Compared the predicted ratings to the gold standard prediction, the RMSE was 0.48.
