MOVIE RECOMMENDATION USING COLLABORATIVE FILTER 

Objective :

The objective of this project is to build a Movie Recommendation System using Collaborative Filtering techniques. The system suggests movies to users based on the preferences and ratings of similar users, using historical data.


Tools & Technologies Used :

Python 3.x

Pandas

NumPy

Scikit-learn

Jupyter Notebook


Dataset

MovieLens Dataset from GroupLens

Contains data on movies, user ratings, and user IDs.

Includes movies.csv, ratings.csv, and sometimes users.csv.


 Project Highlights :

1. Data Preprocessing

Merged movies and ratings datasets.

Handled missing values and duplicates.

Filtered out rare users and movies with very few interactions.



2. Exploratory Data Analysis (EDA)

Analyzed most watched and most highly rated movies.

Visualized user rating distributions.



3. Collaborative Filtering Techniques

Implemented User-Based Collaborative Filtering using cosine similarity.

Implemented Item-Based Collaborative Filtering.

Used the Surprise library to apply algorithms like:

KNNBasic

SVD (Singular Value Decomposition)

KNNWithMeans




4. Evaluation

Used RMSE (Root Mean Square Error) and MAE (Mean Absolute Error) to evaluate performance.

Applied cross-validation using Surprise’s cross_validate.



5. Recommendation Generation

Recommended top N movies to a specific user based on predicted ratings.


How to Run :

1. Clone this repository.


2. Install required packages:

pip install pandas numpy scikit-learn scikit-surprise


3. Run movie_recommender_collab.ipynb in Jupyter Notebook.


4. Modify user ID or movie ID in the prediction cell to get personalized recommendations.


Future Enhancements :

Add hybrid filtering combining content-based and collaborative approaches.

Deploy the model as a web application using Flask or Streamlit.

Integrate user authentication and real-time rating collection.


Author : Sahana Sharon


Dataset Credits : MovieLens Dataset - GroupLens
