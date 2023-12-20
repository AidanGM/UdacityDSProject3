# UdacityDSProject3

## IBM Recommendation Engine

This project is part of my Udacity nanodegree. It uses user-article interactions from IBM Watson Studio to create a recommendation engine.

### Contents

[Packages](#Packages)

[Project Description](#Description)

[Files](#Files)

## Packages <a name="Packages"></a>

The following libraries were used in this project

- pandas 
- numpy
- pickle
- matplotlib

## Project Description <a name="Description"></a>

This project is part of the Udacity Data Science Nanodegree. The goal is to use user-article interactions from IBM Watson Studio to create a recommendation engine.

The main approaches that were considered were:

- **Rank based recommendations**, which recommends the most popular (most interacted-with) articles to users. This is mainly useful for new users where there is less data available to use other approaches.
- **Collaborative Filtering based recommendations**, which recommends articles to users based on which articles similar users have interacted with.
- **Matrix Factorization based recommendations**, which uses SVD (singular value decomposition) on user-item interactions to predict which articles users may want to interact with (read).

## Files <a name="Files"></a>

- `README.md`: Read me file (being read by you now)

- `articles_community.csv`: csv file containing descriptions of the articles on the platform.
- `user-item-interactions.csv`: csv file containing data on user-item interactions

- `Recommendations_with_IBM.ipynb`: Jupyter notebook containing EDA and different recommendation functions
- `Recommendations_with_IBM.html`: HTML file of `Recommendations_with_IBM.ipynb`

