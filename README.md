## Hybrid Recommender System Project
 This project develops a Hybrid Recommender System using Item-based and User-based methods to generate personalized suggestions for specified user IDs. Through collaborative filtering, it aims to improve recommendation quality by harnessing the strengths of both methodologies.


![image](https://i.insider.com/5581afcf69bedd822f53bd2a?width=1000&format=jpeg&auto=webp)


 **************************
## Business Problem:
Generating 10 Movie Recommendations for a Given User ID Using Item-based and User-based Recommender Methods
 **************************

 **************************
## Dataset Story:

The dataset has been provided by MovieLens, a movie recommendation service.
 It includes movies along with the ratings given to these movies.
The dataset comprises 2,000,0263 ratings across 27,278 movies.
It was created on October 17, 2016, containing data from 138,493 users between January 9, 1995, and March 31, 2015.
The users have been selected randomly. It is known that all selected users have voted for at least 20 movies.
 **************************

 **************************


| Variable Name       | Description                                        |
| --------------------|----------------------------------------------------|
| movieId             | Unique movie number (UniqueID)                     |
| title               | Movie name                                         |
| genres              | Genre                                              |
| userId              | Unique user number (UniqueID)                      |
| rating              | Score given to the movie by the user              |
| timestamp           | Rating date                                        |


| Task Title                           | Description                                                                                                           |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| Task 1: Data Preparation             |                                                                                                                       |
| Task 2: Identifying Movies Watched   | by the User to be Recommended                                                                                          |
| Task 3: Accessing Data and IDs       | of Other Users Watching the Same Movies                                                                                |
| Task 4: Identifying Users Most       | Similar to the User to be Recommended                                                                                  |
| Task 5: Calculation of Weighted      | Average Recommendation Score and Keeping the Top 5 Movies                                                             |
| Item-Based Recommendation            |                                                                                                                       |
