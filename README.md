## Machine Learning (Coursera) by Andrew NG

## Project: Recommender System

### Project Overview

I implemented the collaborative filtering learning algorithm and applied it to a dataset of movie ratings to create a recommender system which can be used to suggest movies for users. The dataset consists of ratings on a scale of 1 to 5. The dataset has 943 users, and 1682 movies

#### Project Files

ex8 cofi.m - The main script for the exercise
ex8 movies.mat - Movie Review Dataset
ex8 movieParams.mat - Parameters provided for debugging
checkCostFunction.m - Gradient checking for collaborative filtering
computeNumericalGradient.m - Numerically compute gradients
fmincg.m - Function minimization routine (similar to fminunc)
loadMovieList.m - Loads the list of movies into a cell-array
movie ids.txt - List of movies
normalizeRatings.m - Mean normalization for collaborative filtering
cofiCostFunc.m - Implement the cost function for collaborative filtering
