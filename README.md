# ELT-project

# Source of database

# Name: TMDB 5000 credits 
# From: kaggle
# Link: https://www.kaggle.com/tmdb/tmdb-movie-metadata
# Descrption: It contains movie id, movie name, cast and crew.

# Project Overview

# For this project, I only used the first 100 movies from the original database

# Part I:
# 1. extracted the first actor's name from cast, created wiki urls for each actor and scraped birthday, bithplace, nickname from wikipedia.
# 2. used splitner to run goole search for each moives'reviews (search by keywords "/movie name/ reviews", i.e. "Spider-Man 3 reviews"), from the google results I was able to get IMDB reviews links and critic reviews from various source (this is usually the first result comes up when you run a google search with the keywords above)
# 3. saved the result as a csv for Part II.

# Part II:
# 1. used the file saved from part I, scraped IMDB critic reviews from IMDB reviews pages via IMDB reviews links got from Part I.
# 2. saved the the entire data into sqlite.




