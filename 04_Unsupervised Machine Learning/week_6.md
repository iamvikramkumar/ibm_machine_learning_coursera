# WEEK 6 QUIZ

## Q1. (True/False) In some applications, NMF can make for more human interpretable latent features.
`True`

## Q2. Which of the following set of features is the least adapted to NMF?
`Monthly returns of a set of stock portfolios.`

## Q3. (True/False) The NMF can produce different outputs depending on its initialization.

`True`

## Q4. Which option is the sparse representation of the matrix below?
[(1, 1, 2), (1, 2, 3), (3, 4, 1), (2, 4, 4), (4, 3, 1)]


- [x] [[2 0 0 0],

       [0 3 0 0],

       [0 0 0 1], 

       [0 4 1 0]]


- [ ] [[0 0 0 1],

       [0 2 0 0],

       [0 0 0 3], 

       [0 4 1 0]]
 

- [ ] [[1 0 0 0],

       [0 3 0 0],

       [0 2 0 0],     WRONG

       [0 0 4 2]]


- [ ] [[0 0 0 2],

       [0 3 4 0],

       [0 0 0 0], 

       [0 0 1 0]]


## Q5. In Practice lab: Non-Negative Matrix Factorization, why did we use "pairwise_distances" from scikit-learn?

`To calculate the pairwise distance between NMF encoded version of the original dataset and the encoded query dataset.`
