# Movie Recommendation System

## Project Goals

Learn core concepts of **machine learning** and **recommendation systems** by implementing:
- Popularity-based recommendations
- Content-based filtering (genres, keywords)
- Collaborative filtering (SVD, Surprise library)
- Hybrid recommendation

## Features

- Recommends movies by popularity and user taste.
- Explores content-based similarity (genres, titles).
- Matrix factorization (SVD) collaborative filtering.
- Combines multiple methods for stronger performance.
- Clear Jupyter Notebooks explaining each concept.

## Directory Layout

| Folder/File         | Purpose                                      |
|---------------------|----------------------------------------------|
| `data/`             | Movie/ratings CSV datasets                   |
| `notebooks/`        | Jupyter notebooks for each method            |
| `src/`              | Helper code (data loading, ML functions)     |
| `requirements.txt`  | Dependencies list                            |
| `.gitignore`        | Files to ignore in version control           |

## Setup

1. **Clone repo**:  
    ```
    git clone https://github.com/<your_username>/movie-recommender.git
    cd movie-recommender
    ```

2. **Create Python 3.13 virtual environment**:  
    ```
    python -m venv venv
    source venv/bin/activate           # Linux/Mac
    .\venv\Scripts\activate            # Windows
    ```

3. **Install requirements**:  
    ```
    pip install -r requirements.txt
    ```

4. **Add datasets**:  
    Place your `movies.csv` and `ratings.csv` in the `data/` folder.

5. **Launch Jupyter**:  
    ```
    jupyter notebook
    ```
    Open notebooks inside the `notebooks/` directory.