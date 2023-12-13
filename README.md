# How have the musical components and density of  “one hit wonders” changed over time?

## Motivation
Music has been a passion of mine for as long as I can remember. I’ve always been interested in hit songs and the oddity is a “one hit wonder”. Finding the Spotify API peaked my interest because of the unique audio features in each song that I’ll be able to find for each song that will paint a picture of how these hit songs have changed as well as how the density of these songs have changed over the years.

## Process
The question I am attempting to answer is if the musical components and density of "one hit wonders" have changed over time and if this can be effectively visualized.  With Spotify API, it gives a clear way of collecting concrete song information. The second objective is finding the correct amount of songs and the right songs to accurately reflect my findings. I found a pre-made dataset on kaggle which can be seen [here](https://www.kaggle.com/datasets/dhruvildave/billboard-the-hot-100-songs), and has a full collection of billboard hot 100 songs spanning back to 1958. In order to find a collection of songs that accurately reflected a "one hit wonder" I used Python to filter down songs that were an artist's only chart-topping song and occured between 1980 and 2019. After I had preferrable data, I ran the songs through the Spotify API in order to retrieve the audio features of each song. *Will add as I progress*. I also brought in another curated dataset from Kaggle of sales data from the RIAA (recording industry of america) to provide insight into how music was consumed during this time period. This data can be found [here](https://www.kaggle.com/datasets/andrewmvd/music-sales).

## Introduction to notebook 
### The driver behind my project
> The most important document in my repository is SpotifyAPI.py which I used to have pre-coded functions that can send access requests directly to the API in order to retrieve important song information

### SpotifyAPI.py
> SpotifyAPI.py is a custom module I wrote to help me interact with Spotify's API service. It includes functions that interact with each endpoint and return the response from that endpoint. This is a usable module for anyone interested in playing with the SpotifyAPI, all you would need to do is substitute in your API key into the get_token() function. 

### difficulties
> Many aspects of this project brought difficulties, such as what parameters I wanted to set in order to get an accurate dataset together. Constructing the SpotifyAPI to find song information automatically was a massive hurdle that has occupied a large amount of time spent on gathering data.

## Results
> to be determined

## Technologies Used
* Python
* Spotify API
* Tableau