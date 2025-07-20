# 🎬 Movie Recommender System

This is a simple **Movie Recommender System** built using Python in a Jupyter Notebook. It suggests similar movies based on user input using content-based filtering.

## 📁 Project Structure
```
movie-recommender-system/
├── movie-recommender-system.ipynb
├── dataset/ (optional - if you have CSV files)
│   └── movies.csv
└── README.md
```

## 🚀 Features
- Suggests top similar movies based on a selected movie
- Uses NLP techniques like TF-IDF or CountVectorizer
- Built using Jupyter Notebook for interactive development
- Uses cosine similarity for recommendation

## 🧠 Technologies Used
- Python 🐍
- Jupyter Notebook 📓
- Pandas
- Scikit-learn
- Numpy
- Cosine Similarity

## 📦 Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Aayushlearner/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## 📝 Usage
1. Open `movie-recommender-system.ipynb`.
2. Run all cells in order.
3. Enter a movie name in the input cell.
4. Get a list of similar recommended movies.

## 📊 Example
```python
Input Movie: Inception
Top 5 Recommendations:
- Interstellar
- The Prestige
- The Dark Knight
- Memento
- Shutter Island
```

## 📚 Dataset
The system uses a dataset containing:
- Movie titles
- Genres / Tags / Descriptions
- (Optionally) Ratings or popularity metrics

You can customize the dataset based on your project needs.

## 🔍 How It Works
1. **Load** the dataset using `pandas`
2. **Preprocess** the data by combining relevant text columns (e.g., genres, tags, description)
3. **Vectorize** the combined text using `CountVectorizer` or `TfidfVectorizer`
4. **Compute similarity** scores between movies using `cosine_similarity`
5. **Recommend** the top N most similar movies

## ✅ Requirements
- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- scikit-learn

Install them using:
```bash
pip install pandas numpy scikit-learn jupyter
```

## 📌 TODO
- Add web interface using Streamlit or Flask
- Add support for collaborative filtering (user-based)
- Deploy as an API or web app

## 📜 License
MIT License. Free to use and modify for learning or commercial purposes.

## 🙌 Acknowledgements
- [TMDb](https://www.themoviedb.org/)
- [IMDB](https://www.imdb.com/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
