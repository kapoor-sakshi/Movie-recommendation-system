# Movie Recommendation System (MRS)

# Features

🔍 Auto-suggest Search: Type part of a movie name and get instant suggestions.

🎯 Personalized Recommendations: Recommends movies similar to your input.

🌐 Web Interface: Clean, responsive UI using HTML, CSS, JavaScript, and Django backend.

📊 Pre-trained Model: Works out of the box with a model trained on the top 2.5K IMDB movies.

📁 Easy Model Swap: Replace the model and dataset with your own via two lines of code.

🖼️ Media Support: Includes background video, logo, and custom styling.

🚀 Deployable: Can run locally or on free cloud platforms like Render.

📦 Modular Code: Easily plug in new recommendation models.

# How it works

1. User Input:

User types a movie name in the search bar.

Auto-suggestion helps with finding movie titles quickly.

2. Data Retrieval:

The app loads preprocessed movie data from a .parquet file stored in the static/ directory.

3. Recommendation Model:

A machine learning model finds and returns similar movies based on the input title.

Model logic is inside recommender/views.py.

4. Output:

Recommended movies are displayed on the web page with a smooth UI.

## Images

   1. Home Screen

      <img src="static/images/ss1.png" alt="Home Screen" />

   2. Navigation Screen

      <img src="static/images/ss2.png" alt="Navigation Screen" />

   3. Search with Auto Suggestion

      <img src="static/images/ss3.png" alt="Search Functionality" />

   4. Recommended Movies

      <img src="static/images/ss4.png" alt="Movie Recommended Results" />


