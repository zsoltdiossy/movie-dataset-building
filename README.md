# Movie dataset building with audience ratings
Building a dataset of movies using web scraping with Python BeautifulSoup.

## Project Description
In this project I use Python's BeautifulSoup package to scrape the Wikipedia pages of all Disney movies.

Building different functions the code iterates over all the unique pages of each Disney movie, gather the relevant information from the Wiki's infobox section, cleans and lastly organizes the data into uniform format. Once all the movies and their details are compiled, we bring in the Rotten Tomatoes, IMDB and Metascore ratings, using a publicly available API.

## Packages and resources

Packages used:
 - BeautifulSoup
 - Requests
 - Pandas
 - Pickle

List of Disney movies: https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films

API: https://omdbapi.com/
