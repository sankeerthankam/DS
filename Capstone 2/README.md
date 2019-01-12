# Recommendation Engine using Movie Lens Data

### Objective
The objective of this project is to build a recommendation system using `content-based` and `collaborative-filtering`. 

### Target Audience and Why
Target audience are the movie watchers. Any movie watcher tend to pick another movie based on certain preferences of the previously watched or liked movies. This opens up certain patterns to explore (either based on movie genre, movie plot, lead actor, lead and supporting actor, director etc.) 

### The Data
Most of the data is gathered from `Kaggle` while additional data required for this project is scraped from IMDB's official website using Python's `tmdbsimple` library.

- Users - `user_id`, `age`,	`sex`,	`occupation`,	`zip_code`
- Movies - `movie_id`, `title`, `release_date`, `video_release_date`, `imdb_url`, `genres`
- Ratings - `user_id`, `movie_id`, `rating`, `timestamp`

After scraping the data, we have some additional data about the movies

- Metadata - `overview`, `tagline`, `description`, `imdb_id`, `title`, `vote_average`, `vote_count`
- Keywords - `id`,	`keywords`

### Approach
The goal of this project is to build recommendation systems using different approaches. Below are the jupyter notebooks and their respective tasks. 

- [Capstone 2](https://github.com/sankeerthankam/Data-Science/blob/master/Capstone%202/Capstone%202.ipynb) - Demonstrates data pre-processing and EDA
- [Web Scraping](https://github.com/sankeerthankam/Data-Science/blob/master/Capstone%202/Web%20Scraping.ipynb) - Code to scrape data from IMDB
- [Popularity Based Recommendation System](https://github.com/sankeerthankam/Data-Science/blob/master/Capstone%202/Popularity%20Based%20Recommendation%20System.ipynb) - Code for Popularity Based Recommendation System 
- [Description Based Recommendation System](https://github.com/sankeerthankam/Data-Science/blob/master/Capstone%202/Description%20Based%20Recommendation%20System.ipynb) - Code for Description Based Recommendation System 
- [Metadata Based Recommendation System](https://github.com/sankeerthankam/Data-Science/blob/master/Capstone%202/Metadata%20Based%20Recommendation%20System.ipynb) - Code for Metadata Based Recommendation System 
- [Collaborative Filtering](https://github.com/sankeerthankam/Data-Science/blob/master/Capstone%202/Collaborative%20Filtering.ipynb) - Code for Collaborative Filtering 

### Deliverables
Jupyter Notebooks, Full Project Report, Mini Report and Presentation.
