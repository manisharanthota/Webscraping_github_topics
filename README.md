# Webscraping_github_topics
The project is divided into 2 main parts
First parts request the webpage of github.
It requests upto 5 pages and scrapes the list of topics,usernames and link to the topics
The requestes information is parsed using Beautifulsoup library and then converted into a DataFrame using pandas library
The second parts involves scraping number of stars and topic's repo name and username for each topic
code iterates over the data frame and for each topic gets information from upto 5 webpages
And for each topic a seperate csv file is created with uername,reponame and number of stars
