# A Guide to Selecting Your Next Craft Beer
---
### Objective
The objective of this project is to build a recommendation system using `content-based` and `collaborative-filtering`. 

---
### Target Audience and Why

---
### The Data
Most of the data is gathered from `Kaggle` while additional data required for this project is scraped from IMDB's official website using Python's `tmdbsimple` library.

---
### Approach
Leverage Python’s rich libraries to pull the data via API (in JSON format) calls for analysis.
Since I am limited to 100 API calls per hour and 50 records per call, I will write a script to pull as much data as I can at one time and repeat until I have a complete dataset.
Create my personal beer list (~200 distinct beers) and analyze/clean data.
Create untasted beer list (~10,000+ distinct beers) and analyze/clean data.
Analysis and factor engineering: understand key drivers to beer ratings.
Leverage machine learning methodologies, test multiple algorithms for prediction approach. Select best algorithm.
Build prediction ratings from ~200 distinct beers and extract upon 10,000+ beers based on a unique user’s ratings data.
Build prediction ratings from ~200 distinct beers and extract upon 10,000+ beers based on mass user ratings data.
Compare results from #7 and #8, produce insight and recommendations.
Identify challenges with approach / results and provide recommendations on how to improve for future analysis.

---
### Deliverables
Jupyter Notebooks, Full Project Report, Mini Report and Presentation.
