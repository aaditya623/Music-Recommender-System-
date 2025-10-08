# Music-Recommender-System-
This project is a Music Recommender System that suggests songs to users based on the lyrics or text description of other songs. It helps people discover songs similar in theme, emotion, or content to the ones they already enjoy. 


The dataset used contains only four columns — artist, song, text, and link.

artist → name of the singer or band

song → name of the track

text → lyrics or description of the song

link → YouTube or music link for easy access

The system analyzes the text column (lyrics) to find similarities between songs using Natural Language Processing (NLP) techniques.


How It Works

The lyrics or text of each song are cleaned and processed (removing stopwords, punctuation, etc).

The system converts the text into numerical form using TF-IDF Vectorization.

Using Cosine Similarity, it calculates how similar each song is to the one selected by the user.

It then displays a list of songs that have similar lyrics or emotions, along with their artist names and clickable links.
