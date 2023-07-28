# Recommender-Systems
## Matrix Factorization

The primary goal of this tutorial is to provide a comprehensive understanding of how sparse recommender systems are stored and how to effectively utilize sparse matrices. Additionally, the tutorial aims to guide learners through the process of implementing matrix factorization algorithm for recommenders.

Our task is to use matrix factorization and cross-validation to achieve the best performance (lowest MSE). Here's what we need to do:

* Rate 3 to 5 of the movies from the table given above and add this information to the end of the data set. For example, if you rate _Home Alone_ as 4 stars, add the entry np.array([902,9,3]) to the data set.
* Find the best hyperparameters $\lambda$, $n\_interactions$, and $n\_factors$ using one of the validation procedures that we have covered in a previous lecture
* Predict all the ratings for user 0 using the best hyperparameters that you found. Save the predicted ratings in an array and then save the array in a file with the extension _.npy_. For example, you can use _np.save("/home/name_group.npy",u0)_.
