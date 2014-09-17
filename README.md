imdb-scraper
============

IMDB Scraper - This app is created using Python, Django and Beautiful Soup to scrape the movie details from IMDB Top 250 Chart.

Videos are displayed on homepage as per the count set by admin using paginator.

Uses sqlite database for storing video details.

You may delete the database and know its working after you execute the command, python manage.py syncdb,
and going to url, http://127.0.0.1:8000/scrape

Please wait once you execute the above URL as the data will take some time to get populated.
