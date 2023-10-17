# WEEK 3 QUIZ

## Q1. For the user profile matrix you generated in the User Profile-based Recommender System Lab, what does each row represent?

`User profile vector`

## Q2. For the User Profile-based Recommender System Lab, which of the following best describes a user profile vector?
`A list of recommendation scores `

## Q3. For the User Profile-based Recommender System Lab, how is each value calculated in the user profile matrix you created?

`The dot product of a user’s course ratings vector by a course’s associated genres vector`


## Q4. For the User Profile-based Recommender System Lab, what does each cell value represent in the recommender score matrix you created?

`A course recommendation score for a given user`

## Q5. For the Content-based Recommender System Lab, why are the values along the diagonal equal to 1 in the course similarity matrix?

`Because the similarity measurement of a course compared to itself is equal to 1`

## Q6. What information does the course similarity matrix discussed in Content-based Recommender System Lab convey?

`Displays the bag of words similarity measurements between all courses to all other courses`


## Q7. What do the indices in the course similarity matrix from Content-based Recommender System Lab represent?

`Courses`

## Q8. In the following code, sim_df represents a course similarity matrix.

sim_matrix = sim_df.to_numpy()

sim = sim_matrix[200][158]

sim

What does the output of this code represent?

`The similarity measurement between the courses with indices 200 and 158`


## Q9. In the Clustering-based Course Recommender System Lab, which of the following ranges contains the point that indicates the optimized number of clusters in order to apply the K-means algorithm to generate the cluster label for all users?

`11-20`

## Q10. In the Clustering-based Course Recommender System Lab, which of the following pairs of course genres are the most highly correlated according to the covariance matrix?

`Python and DataAnalysis`
