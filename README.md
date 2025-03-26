# Movie Recommendation System

This project is a **Movie Recommendation System** that uses **k-nearest neighbors (KNN)** to suggest similar movies based on user ratings. The system utilizes **cosine similarity** to find nearest neighbors and recommends movies accordingly.

## Features
- Uses **KNN with cosine similarity** to find similar movies.
- Supports **fuzzy matching** to handle variations in movie titles.
- Based on a dataset of movies and user ratings.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/rohanrony19/Movie-Recommendation-System
   cd Movie-Recommendation-System
   ```
2. Install required dependencies:
   ```bash
   pip install pandas numpy scipy scikit-learn fuzzywuzzy
   ```

## Usage
1. Run the Jupyter Notebook:
   ```bash
   jupyter notebook movie_recommendation.ipynb
   ```
2. Enter a movie name to get recommendations:
   ```python
   recommender('movie name', mat_movies, 10)
   ```
## Dataset
- **Movies Dataset**: https://raw.githubusercontent.com/Praful2000/YoutubeLectures/master/Movie%20KNN/movies.csv
- **Ratings Dataset**: https://raw.githubusercontent.com/Praful2000/YoutubeLectures/master/Movie%20KNN/ratings.csv

## Dependencies
- Python 3.10
- Pandas
- NumPy
- SciPy
- Scikit-learn
- FuzzyWuzzy

## Results
![Screenshot 2025-03-26 160728](https://github.com/user-attachments/assets/be90f888-0bc1-4279-b752-ad431e6fa8ab)

![Screenshot 2025-03-26 155643](https://github.com/user-attachments/assets/7327d212-03ec-4ef8-950b-369f2a679b51)


## License
This project is licensed under the MIT License.

