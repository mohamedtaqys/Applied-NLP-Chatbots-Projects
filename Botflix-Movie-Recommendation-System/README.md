# **Botflix - Movie Recommendation System**
Botflix is a movie recommendation system designed to help users discover movies they might enjoy. It uses content-based filtering to recommend movies based on genres and provides additional functionalities like searching for movies, suggesting random movies, and finding top movies by theme. The system is interactive and user-friendly, making it easy for users to explore and find their next favorite movie.

## Data Source  
This project uses the **TMDB Movie Metadata** dataset from Kaggle:  
- **Dataset**: [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)  
- **Provider**: [TMDb (The Movie Database)](https://www.themoviedb.org/)  
- **Kaggle Publisher**: [Kaggle user "tmdb"](https://www.kaggle.com/tmdb)  
- **License**: [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) (Creative Commons Attribution-NonCommercial)  

## Features
1. Movie Recommendations:
  - Recommends movies similar to a given movie based on genres.
  - Displays detailed information about each recommended movie, including:
    - Title
    - Genres
    - Release Date
    - Runtime
    - Rating
    - Overview (description)

2. Top-N Movies by Theme:
  Displays the top-rated movies in a specific genre or theme (e.g., Action, Comedy, Drama).

3. Advanced Search:
  Allows users to search for movies by:
    - Title: Search for movies by their title.
    - Year: Search for movies released in a specific year.
    - Actor: Search for movies featuring a specific actor.
    - Rating: Search for movies with a minimum rating.

4. Random Movie Suggestion:
  Suggests a random movie with all its details.

5. Interactive Chatbot:
  - Provides a user-friendly interface for interacting with the system.
  - Guides users through the available functionalities.

## Setup 🛠️

### Prerequisites
- pandas>=1.3.0
- numpy>=1.21.0
- scikit-learn>=1.0.0

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/mohamedtaqysalmi/Applied-NLP-Chatbots-Projects.git
   cd Botflix-Movie-Recommendation-System
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook Botflix.ipynb
   ```

## File Structure 📂
```
Botflix-Movie-Recommendation-System/
├── BotFlix.ipynb            # Main notebook
├── requirements.txt         # Dependencies
└── README.md
```

## Dependencies 📦
Listed in `requirements.txt`:
```
pandas>=1.3.0
numpy>=1.21.0
scikit-learn>=1.0.0
```

## License 📜
MIT License. 

---

**Author**: [Mohamed-Taqy Salmi](https://linkedin.com/in/mohamedtaqysalmi)  
**Contribute**: PRs and issues welcome!  
```
