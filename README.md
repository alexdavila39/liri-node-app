  # liri-node-app



## Motivation
This is a project for UCF's Coding bootcamp class where we are learning to implement node.js.

## What Each Command Does

##### node liri.js concert-this <artist/band name here>

 * This will search the Bands in Town Artist Events API ("https://rest.bandsintown.com/artists/" + artist + "/events?       app_id=codingbootcamp") for an artist and render the following information about each event to the terminal:

  - Name of the venue
  - Venue location
  - Date of the Event (use moment to format this as "MM/DD/YYYY")

* node liri.js spotify-this-song '<song name here>'

* This will show the following information about the song in your terminal/bash window

- Artist(s)
- The song's name
- A preview link of the song from Spotify
- The album that the song is from

* node liri.js movie-this <movie name>
* Shows the following information in terminal/bash.

- Title of the movie.
- Year the movie came out.
- IMDB Rating of the movie.
- Country where the movie was produced.
- Language of the movie.
- Plot of the movie.
- Actors in the movie.
- Rotten Tomatoes Rating.
- Rotten Tomatoes URL.
- Or if no movie is passed through, it will default to "Mr. Nobody"

* node liri.js do-what-it-says
- Takes the text from random.txt and runs the song through spotify-this-song command

### The following commands run without user input:
* node liri.js Concert-this
* node liri.js spotify-this-song
* node liri.js movie-this
* node liri.js do-what-it-says

## NPM Dependencies
* dotenv
* Bands-in-town
* node-spotify-api
* request
* fs

## API Integration
* Bands-in-town
* Spotify
* OMDB


