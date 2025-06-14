# mcommerce-recommendation-system
Content-based recommendation system for mCommerce apps (TF-IDF). Data project focused on marketing analytics and user behavior

# Brazilian mCommerce App Recommender

This project is based on my MBA final thesis in Data Science & Analytics (USP, 2023). The goal was to analyze Brazilian Android users of shopping apps and create a content-based recommendation system to increase the visibility of lesser-known apps.

## Project Objective

- Analyze user demographics, app popularity, and ad investment data
- Understand correlations between advertising and app ranking
- Build a recommendation system using TF-IDF for content similarity

## Techniques Used

- Exploratory Data Analysis (EDA)
- Correlation (Spearman)
- TF-IDF matrix for similarity
- NLP pre-processing (Spacy)
- Python (Pandas, Numpy, Scikit-learn)

## Dataset Overview (simulated)

- App performance (downloads, active users, sessions)
- Demographics (gender, age group)
- User reviews
- Ads investment and creatives

## Recommender Example

Given the app "Shein", the model recommends:
- NewChic – Fashion Online
- Hibobi – Kids Fashion Online
- Light in the box
- Banggood
- Fashion Nova

These are based on genre, title, user profile, and activity level.

## Repository Structure

- `notebooks/`: analysis & model development
- `data/`: anonymized/simulated data used
- `assets/`: charts and images for reference
