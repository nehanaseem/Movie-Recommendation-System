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

To get started with this project, follow these steps:

### Clone the repository:
```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
### Install the required packages:
pip install -r requirements.txt
### Run the Jupyter notebook:
jupyter notebook movie_recommendation_system.ipynb

### 📜 Dataset
The dataset used in this project is from the TMDB 5000 Movie Dataset, containing detailed information about movies including their cast, crew, genres, and more.

### 🤝 Contributing
Feel free to contribute to the project by submitting a pull request. Any ideas or improvements are welcome!
