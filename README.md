# 🎬 Facts behind Fantasy: K-drama Recommender & Analysis
Welcome to our deep dive into the world of Korean dramas!
This project explores the rising popularity of K-dramas, uncovers the hidden patterns behind viewer preferences, and builds a recommendation system to help users discover new favorites.

## 👥 Team Members
Mingyang, Michelle, Hannie, Ethan

## 📊 Data & Methods
📁 Dataset
Source: Top 250 Korean Dramas on Kaggle

Features include:
- Titles
- Genres
- Tags
- Cast
- Directors
- Ratings
- Release Year
- Episode Count
- Duration

## 📈 Key Questions & Insights
📅 When should you air your drama?
Weekends vs Weekdays — we analyzed airing schedules to see what correlates with popularity.

🎭 Do thrills = high ratings?
Dramas with action, cliffhangers, and suspense tend to score higher — are we just harder to impress now?

🔥 What genres are on the rise?
Big genre shifts between the 2010s and 2020s.

## 🤖 Recommendation System
We built a basic content-based recommendation system to suggest similar dramas using vector space modeling:

🧩 How It Works
- Feature Extraction: Genre, tags, cast, episode count, etc.
- TF-IDF Vectorization: Transforms textual metadata into weighted feature vectors.
- Cosine Similarity: Measures how similar two K-dramas are.
- Top 5 Recommendations: Based on similarity scores to a selected show.

🔗 Link to article: https://ucladatares.medium.com/facts-behind-fantasy-dissecting-the-captivating-world-of-korean-dramas-8f4ed7605a08
