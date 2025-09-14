🎬 IMDB Movie Analysis
📌 Project Overview

This project analyzes the IMDB movie dataset to explore patterns, trends, and insights in the film industry.
The dataset includes information such as movie titles, genres, duration, director/actor details, ratings, budget, gross revenue, and more.

Key tasks performed in this project:

Data cleaning & handling missing values.

Exploratory Data Analysis (EDA) 

Visualization of patterns 

Statistical insights

📂 Dataset

The dataset used is movie_metadata.csv from IMDB movie records.

Features include:

color – Movie color type (Color / Black and White).

director_name, actor_1_name, actor_2_name, actor_3_name.

num_critic_for_reviews, num_user_for_reviews.

duration – Runtime of the movie.

gross – Worldwide revenue.

budget – Production cost.

genres – Movie categories.

language, country, content_rating.

imdb_score – IMDB rating (1–10).

title_year, aspect_ratio.

🛠️ Data Cleaning

Missing values were handled carefully:

Categorical (e.g., director, actors, language, country) → replaced with "Unknown".

Duration, critic reviews, user reviews → replaced with median (to reduce skew impact).

Director/actor Facebook likes → replaced with 0 (no data = no likes).

Budget & Gross → imputed using genre-wise mean with fallback to overall mean.

Facenumber in poster, title_year, aspect_ratio, color → filled with mode.
