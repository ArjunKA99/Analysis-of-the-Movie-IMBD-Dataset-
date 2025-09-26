 🎬 IMDb Movie Analysis

 📌 Project Overview

This project analyzes the IMDb Movie Dataset to uncover meaningful insights into the film industry. By applying Exploratory Data Analysis (EDA) and visualization techniques, the goal was to study how factors like budget, revenue, genres, and ratings are interrelated and what drives a movie’s success.

The work carried out includes:

 Data cleaning and preprocessing
 Handling missing values and inconsistencies
 Exploratory analysis of single and multiple variables
 Visualizations to highlight industry patterns and trends
 Statistical insights for budget, revenue, and rating relationships
 Final conclusions based on findings

---

 📂 Dataset

The dataset used is movie_metadata.csv, consisting of IMDb movie records with 28 columns.

Key features include:

 color – Color type (Color / Black and White)
 director_name, actor_1_name, actor_2_name, actor_3_name – Crew information
 duration – Runtime (minutes)
 budget – Production cost
 gross – Worldwide revenue
 genres – Primary and secondary categories
 imdb_score – IMDb rating (1–10)
 num_critic_for_reviews, num_user_for_reviews – Review statistics
 language, country, content_rating – Production details
 title_year, aspect_ratio – Additional metadata

---

 🛠️ Data Cleaning & Preprocessing

Several missing values were addressed using appropriate strategies:

 Categorical values (director, actors, language, country) → replaced with `"Unknown"`
 Duration, critic reviews, user reviews → filled with median values
 Director/actor Facebook likes → replaced with `0` (no data = no likes)
 Budget & Gross revenue → imputed using genre-wise mean (fallback to overall mean)
 Facenumber in poster, title_year, aspect_ratio, color → filled with mode

---

 📊 Analysis & Visualizations

 Genre Analysis → Identified top genres by frequency and average IMDb ratings
 Budget vs. Gross Revenue → Positive correlation, though some high-budget films underperformed
 Duration vs. IMDb Score → No strong correlation, but mid-length films tend to score higher
 Actor & Director Popularity → Certain individuals consistently linked with successful films
 Revenue & Ratings → Commercial success doesn’t always align with critical acclaim

Visualizations were built using Matplotlib, Seaborn, and Plotly for clarity and interactivity.

---

 ✅ Key Insights & Conclusion

1. Budget and revenue are positively correlated, but a high budget doesn’t guarantee success.
2. IMDb score and revenue are weakly correlated, showing that critically acclaimed movies aren’t always the most profitable.
3. Genres like Drama and Comedy dominate the industry, but Action and Adventure drive higher revenues.
4. Duration impacts audience reception – movies with very short or very long runtimes tend to score lower.
5. Star power matters – popular directors and lead actors have a measurable impact on performance.

Final Note:
This analysis highlights that while financial investment and big names influence a movie’s success, audience perception is more nuanced. Storytelling quality, genre appeal, and balanced production decisions play equally crucial roles in determining both commercial and critical success.

---
