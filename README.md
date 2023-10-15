# Movie Recommender System

This repository contains a content-based movie recommender system. The system recommends movies to users based on their movie preferences. It leverages content-based filtering techniques to provide personalized movie recommendations.

## Features

- Recommends movies based on user preferences.
- Utilizes movie metadata and user input to make recommendations.
- Provides a simple, user-friendly interface for input and recommendations.

## Usage

### Running the Recommender System

1. To use the Movie Recommender System, clone this repository to your local machine:
   ```bash
   git clone https://github.com/Asrivast1/Content-Based-Recommender-System.git
   ```
   
2. Install Jupyter Notebook if you haven't already:
   ```bash
   pip install jupyter
   ```
   
3. Navigate to the cloned repository:
   ```bash
   cd Content-Based-Recommender-System
   ```
   
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
   
5. In your web browser, a new tab will open with the Jupyter Notebook interface. Locate and open the **content_based_movie_predictor.ipynb** to access the recommender system.
6. Follow the instructions within the notebook to input your movie preferences and receive personalized movie recommendations. Pass your preferred movie as the first argument in get_recommendations method and use cosine_sim2 as second parameter and it'll return the top 10 most similar movies.

### Data Source
The movie data used by the recommender system is obtained from [The movies metadata dataset on Kaggle](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=movies_metadata.csv). You can find the dataset and more information there.

#### Do consider to star this project if you find it useful ⭐
