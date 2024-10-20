# Hybrid Movie Recommendation system 
Data Preprocessing and Cleaning : Handle missing values, format inconsistencies, and normalize relevant data fields.

Collaborative Filtering Implementation : Implement matrix factorization (e.g., SVD) for collaborative filtering using a user-item interaction matrix.

Content-Based Filtering Implementation : Build a content-based filtering system using TF-IDF vectorization and cosine similarity.


Hybrid System Integration : Combine collaborative filtering and content-based filtering results to form a hybrid recommendation system.

# Content based filtering 
The TFIFDVectorizer is used for text vectorization, with cosine similarity to find the similar result as the user  enters their requirement


# Collaborative Filtering 
The SVD model from suprise module with proper hyperparameter tuning for adjusting the  weight to the model, cross validation to evaluate the model on 5 folds, is used to       
recommend the movies with similar ratings. 

###  Hybrid system is implement with merge of both content based filtering and collaborative filtering with proper input validation. 

### Additional Feautures is added where the user can enter the country name and  the movie is recommended on  the basis of country origin 

