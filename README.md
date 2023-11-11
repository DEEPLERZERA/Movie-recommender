# Movie-recommender
Movie recommender, built with numpy library in Python. 

In this project we have two types of recommender, that is called by: **Collaborative Filtering** and **Content-Based Filtering**.

## Collaborative Filtering
![image](https://github.com/DEEPLERZERA/Movie-recommender/assets/73613620/9ed7b85d-83f5-4bcb-928a-384a785cd5c4)

Here you have **collaboration** as the basis for our filter, if someone likes a video and another user likes it, and if that user likes another video, that video will be shown to the other user as in the **illustration**.

## Content-Based Filtering
![image](https://github.com/DEEPLERZERA/Movie-recommender/assets/73613620/ffa521ee-f682-477e-9475-71a088022f22)

Here you have the **similarity** of a video as the basis for our filter, if someone likes a video, and the other video is similar to this video liked by someone, that video will be shown to the user, as is in the **illustration**.

## Cosine similarity
![image](https://github.com/DEEPLERZERA/Movie-recommender/assets/73613620/84d30610-45a1-41e6-84a1-9a6bbab55b96)

In these two types of recommender, we use the **cosine similarity** to build the filter, basically if the **cosine** is high or equal to 1 we have two identical or similar movies, and when we have a low **cosine** as 0.001, we have no similarity between these two movies.
