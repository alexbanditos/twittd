# twittd
twittd is a project that collects twiits from twitted accoding to predefined key words and store them in a DB.

# How
Using docker-compose 2 contianer will be created, the first is based on python 3 machine and will hold the script on it and the other will be mongodb machine with a link between the contianer.
Using Tweepy python module we connect to twitter API and collect DATA with prefedined key words (you can collect data for the last 7 days with the free API). 
this data is collected to mongoDB for future use.


# Dependecies
Docker 
Docker-Compose
MongoDB Client
Tweepy

