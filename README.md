# BOOK-Recommender-System
dataset link :- https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset
this is a book recommendation system in this project i have built 2 main recommendation system 
and those are popularity based and collaborative filtering based recommendation systems 
1)popularity based
we recommend each and every user the most popular 50 books
and we extracted those books on the number of the ratings on that book
and then we sorted the list in desecting order of the avgerage rating for each book
2)collaborative filtering based
It recommends the book on the basis of ratings received from the particular no.
of users first we build a table which contains true_readers here true_readers means
the users that have rated more than 200 books and the table will contain the books 
that are rated by more than 50 readers
and we have used the library cosine_similarity which helps us to get the similarity 
score of each book with each and every other book and the book that have maximum similarities
will be recommended and so on and so forth
