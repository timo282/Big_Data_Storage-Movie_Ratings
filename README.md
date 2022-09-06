# Big Data Storage - Movie Ratings

Exam for lecture *Big Data Storage* at DHBW Ravensburg.

## Group Task
You are given the following three data set files:
- credits_groupC.csv
- movies_groupC.csv
- recommendations_groupC.csv (contains information from an online streaming site about how the users rated the movies)

Please answer the following questions based on the provided datasets and by using Apache Spark. The programming has to be done in Python.

Use a proper storage structure so you would be able to also handle millions of movies and a significant increase in recommendations.

1. Which movie genres have the most movies with a runtime over 120 minutes and how many movies? Please list the top three movie genres.
2. In how many movies did the actor Johnny Depp take part in as an actor? In how many of those did he also act as a producer?
3. List the names and the revenue of the ten movies with the most revenue which were released before 2015. What are the ten financially most succesful movies when comparing the revenue to the budget?
4. What is the movie genre that has a median rating of at least 3 (over all movies with at least ten recommendations) with the lowest average production budget considering all movies?

## Individual Task

How many movies where written by a female writer?

Explain what data storage structure you used to store the information and why. When storing the information how can you speed up the information retrieval if you know you are interested in looking at the gender of the writer? Why does it speed up the information retrieval when you store the data differently?
