# Smart Movie Recommendation and Discovery System

A machine learning based movie recommendation and discovery system built using the MovieLens dataset.

##  Project Overview

This project analyzes movie ratings and genres to build a movie recommendation system. It provides movie recommendations based on movie similarity and also provides mood-based movie recommendations.

The project combines data analysis, feature engineering, and machine learning techniques to explore movie preferences and recommend relevant movies.

##  Features

*  Movie rating analysis
*  Genre analysis
*  Movie rating and popularity analysis
*  Hidden gem movie identification
*  Movie-to-movie recommendations
*  Mood-based movie recommendations
*  Content-based filtering
*  TF-IDF feature extraction
*  Cosine similarity for finding similar movies
*  Handles invalid movie names and moods

##  Recommendation Methods

### 1. Content-Based Movie Recommendation

The system recommends movies similar to a selected movie by analyzing movie genres.

It uses:

**TF-IDF → Cosine Similarity → Similar Movies**

For example:

```text
Input:
Toy Story (1995)

Output:
Similar movies based on genre similarity
```

### 2. Mood-Based Recommendation

The system maps moods to movie genres using predefined rules.

| Mood      | Genres            |
| --------- | ----------------- |
| Happy     | Comedy, Animation |
| Romantic  | Romance           |
| Scary     | Horror, Thriller  |
| Adventure | Adventure, Action |
| Emotional | Drama, Romance    |

For example:

```text
Input:
happy

Output:
Movies from Comedy and Animation genres
```

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook
* MovieLens Dataset

##  Project Structure

```text
movies_project/
│
├── data/
│   └── MovieLens dataset files
│
├── movielens_dataset.ipynb
│
├── README.md
│
└── .gitignore
```

##  Data Analysis

The project performs analysis on:

* Movie ratings
* Average movie ratings
* Number of ratings per movie
* Movie genres
* Popular movies
* Hidden gems

##  How It Works

```text
MovieLens Dataset
       ↓
Data Loading
       ↓
Data Cleaning
       ↓
Dataset Merging
       ↓
Exploratory Data Analysis
       ↓
Genre Analysis
       ↓
TF-IDF Feature Extraction
       ↓
Cosine Similarity
       ↓
Movie Recommendation
       ↓
Mood-Based Recommendation
```

##  How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the project

```bash
cd smart-movie-recommendation-system
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib scikit-learn jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open

```text
movielens_dataset.ipynb
```

Run the notebook cells in order.

##  Dataset

This project uses the **MovieLens dataset** containing movie information, user information, genres, and ratings.

The dataset is used for educational and machine learning purposes.

##  Learning Outcomes

Through this project, I learned how to:

* Work with real-world datasets
* Clean and prepare data using Pandas
* Perform exploratory data analysis
* Analyze movie ratings and genres
* Apply TF-IDF feature extraction
* Calculate cosine similarity
* Build a content-based recommendation system
* Create a rule-based mood recommendation feature
* Handle invalid user inputs
* Organize and document a machine learning project

##  Future Improvements

* Add a Streamlit web interface
* Add user-based recommendations
* Build a hybrid recommendation system
* Improve mood-based recommendations
* Add recommendation evaluation metrics
* Allow users to create personalized movie profiles

