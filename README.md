<img src = "https://www.rottentomatoes.com/assets/pizza-pie/head-assets/images/RT_TwitterCard_2018.jpg" width=20% height=20%>

# Web-scraping Analysis - Rotten Tomatoes

In this project, data has been scraped from Rotten Tomatoes' 'Worst Blockbusters of All Time Ranked' page. 
The primary objective of this project is to analyze and extract insights from the data, focusing on frequent movie names, actors/actresses, directors, and release years.
You can access the website, 'Worst Blockbusters of All Time Ranked,' through this link: https://editorial.rottentomatoes.com/guide/worst-blockbusters/"

## Overview
I performed web scraping to extract data, including movie names, release years, ratings, directors, and cast information.
This data was organized and presented in a Pandas DataFrame. 
The table is sorted in descending order based on the movie ratings, with the lowest-rated blockbuster at the top."

<img src = "https://github.com/DCCheryl/Web-scraping-project-/assets/53252746/90b64fe4-b5a4-45bc-8e23-4946204f52f2" width=70% height=70%>

## Top 15 actor/actress of the worst blockbuster movies
The bar chart reveals that Adam Sandler stands out by appearing in six of the worst blockbuster movies, 
followed by Dakota Johnson, Jamie Dornan, Kevin James, Jon Favreau, and Mark Wahlberg, each featuring in three movies. 
It's important to note that while Adam Sandler is prominently featured in this list, 
he is still considered a talented actor, having delivered commendable performances in other movies, including 'Anger Management' (2003), 'Click' (2006), and 'Pixels' (2015).

<img src = "https://github.com/DCCheryl/Web-scraping-project-/assets/53252746/6df85a15-b052-4792-959f-4f35006279d6" width=70% height=70%>


## Top 15 directors of the worst blockbuster movies
The bar chart highlights that Michael Bay holds the record for directing five of the worst blockbuster movies, while Dennis Dugan follows closely with four movies to his name. 
Let's delve into the individual movies directed by these filmmakers to understand why they've taken their positions on the worst blockbuster list.

<img src = "https://github.com/DCCheryl/Web-scraping-project-/assets/53252746/97e6276b-fae8-4b64-91da-a12711d7a870" width=70% height=70%>


## Top 10 words in the name of the worst blockbuster movies
From the list, we have identified some keywords, excluding common words like 'the,' 'and,' and 'of.' 
The bar chart reveals the frequency of these keywords in movie names: "Fifty", "Wild", "Alvin", "Shades" and "Transformers".
These keywords appear three times each, while "Saga," "Ups," "Grown," "Chipmunks," and "Twilight" appear two times. 
Further examination of the word and matching movie table reveals that several of these keywords are linked to movie series found on the list of the worst blockbuster movies., 
For instance, we have the following movie series:

    "Fifty Shades"
    "Transformers"
    "Alvin and the Chipmunks"
    "The Twilight Saga"
    "The Grown Ups"

It's noteworthy that both "Transformers" series, directed by Michael Bay, and "The Grown Ups" series, directed by Dennis Dugan, have secured top positions in the list of worst blockbuster movies. 
This correlation is why these directors top the list of worst blockbusters.

<img src = "https://github.com/DCCheryl/Web-scraping-project-/assets/53252746/4149425f-76b9-4658-84af-e0515ab53601" width=70% height=70%>

<img src = "https://github.com/DCCheryl/Web-scraping-project-/assets/53252746/62cda942-24f9-4cb2-808a-d1039109fd39" width=70% height=70%>


## Top 15 release years in the worst blockbuster movies list
The bar chart reveals that a significant number of the worst blockbuster movies were released in 2010 and 2009, with 2007 following closely behind.

<img src = "https://github.com/DCCheryl/Web-scraping-project-/assets/53252746/30efdc58-a5b1-4d59-b760-c6b5045a017c" width=70% height=70%>
