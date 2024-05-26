# Movie Recommender System

## Project Overview
This project develops a simple yet effective recommender system based on the small MovieLens dataset, focusing on providing movie recommendations according to user input. Utilizing content-based filtering, the system leverages movie genres as the primary feature for establishing similarity among movies, thereby recommending titles similar to a user's preferences.

## Technical Approach
- **Data Loading:** The small MovieLens dataset, which includes movies with titles and genres along with user ratings, serves as the foundation for analysis.
- **Preprocessing:** A critical step where movie titles are merged with their ratings, and genres are processed using TF-IDF vectorization to prepare the data for similarity scoring.
- **Similarity Measure:** Cosine similarity, employed on the genre vectors, facilitates the calculation of similarity scores between movies, treating each genre as a vector dimension.
- **Recommendation Logic:** Upon receiving a movie title from the user, the system identifies the top 10 most similar movies based on their similarity scores, excluding the input movie itself.
- **Output Presentation:** The recommended movies are presented to the user, showcasing the system's capability to tailor suggestions based on content similarity.

## Example Usage
An example query for the movie "Jumanji (1995)" demonstrates the recommender system's ability to suggest titles like "Indian in the Cupboard, The (1995)", "NeverEnding Story III, The (1994)", and "Harry Potter and the Sorcerer's Stone (a.k.a. Harry Potter and the Philosopher's Stone) (2001)", among others, showcasing its efficacy in identifying genre-aligned recommendations.

## Development Insights
The project highlights the application of content-based filtering techniques in recommender systems, specifically focusing on:
- The importance of preprocessing and feature extraction for effective recommendation.
- Utilizing cosine similarity to measure content similarity based on genres.
- The practical implementation of a recommender system that can be further expanded or refined with additional features or filtering methods.

## Conclusion and Reflection
This genre-based recommender system represents a foundational approach to understanding and implementing recommender systems. While it employs a basic content-based filtering methodology, it underscores the potential for more sophisticated systems that incorporate collaborative filtering, deep learning models, or hybrid approaches for enhanced recommendation accuracy and personalization.

## References
- GroupLens Research. (2024). MovieLens Dataset. Retrieved from GroupLens
