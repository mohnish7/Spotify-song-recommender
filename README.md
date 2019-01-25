# Spotify-song-recommender
Analyzing attributes of the songs in your library and automatically adding recommended songs from a given playlist back to your library.

<b>Contributors:</b>
<ul>
  <li>Anant Majumdar</li>
  <li>Mohnish Chakravarti</li>
  </ul>

Methods used: k-NN, and a euclidean distance-based approach where we check if the value of the song's attributes fall within a certain range of your playlist's average.

<b> Note: </b>
You need to register yourself with Spotify's API to get your own client ID, client secret and set a redirect uri for yourself. Go to https://developer.spotify.com/dashboard/applications/ for more info

You also need to make a playlist of disliked songs for this to work. We assume your list of saved songs to be your playlist of liked songs
