# 🎬 Movie Recommendation System 🎥

This project demonstrates the creation of a Content-Based Movie Recommendation System using metadata such as genres, keywords, cast, and crew from the TMDB 5000 dataset. By leveraging cosine similarity, it identifies and suggests movies similar to a given title.

## 🌟 Features
- 🎭 **Metadata Extraction:** Extract key details like genres, cast, crew, and keywords.
- 🎯 **Content-Based Recommendations:** Recommends similar movies based on metadata similarity.
- 📊 **Visual Insights:** Graphs and charts showcasing genre distributions, cast frequencies, and more.
- 🔍 **Cosine Similarity:** Computes similarity between movies to offer personalized recommendations.

## 📂 Project Structure
- `tmdb_5000_movies.csv`: Contains movie-related information.
- `tmdb_5000_credits.csv`: Contains cast and crew information.
- `movie_recommendation_system.ipynb`: Jupyter notebook with the code for extracting features, computing similarities, and generating recommendations.

### Visualizations:
- 🎬 **Top Genres Distribution**
- 🔑 **Top Keywords Frequency**
- 🎭 **Top Cast and Directors**
- 🔥 **Cosine Similarity Heatmap** (Sample for 10 movies)

## 🚀 Getting Started

### Clone the repository:
```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
## Install the required packages:
pip install -r requirements.txt
## Run the Jupyter notebook:
jupyter notebook movie_recommendation_system.ipynb


📊 Visualizations
Top Genres Distribution: Bar chart representing the most frequent genres.
Top Keywords Distribution: Visualization of the most commonly used keywords in movies.
Top Cast Members Frequency: Highlights frequently appearing actors across movies.
Top Directors Frequency: Insights into the most active directors in the dataset.
Cosine Similarity Heatmap: Displays the similarity scores between 10 selected movies.
Sample Visualization - Top Genres Distribution

📜 Dataset
The dataset used in this project is from the TMDB 5000 Movie Dataset, containing detailed information about movies including their cast, crew, genres, and more.

🤝 Contributing
Feel free to contribute to the project by submitting a pull request. Any ideas or improvements are welcome!
