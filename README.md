# Spotify Scraper & Playlist Creator

This Python project enables users to scrape the top 100 songs of a specified date and year from Spotify and create a playlist containing those songs on the user's Spotify account. It leverages the Spotify Web API for retrieving song data and managing playlists.

## Features

- **Top 100 Songs Scraper**: Scrapes the top 100 songs from Spotify for a specified date and year.
- **Spotify Authentication**: Authenticates the user with Spotify to access their account and create playlists.
- **Playlist Creation**: Creates a new playlist on the user's Spotify account.
- **Adding Songs to Playlist**: Adds the scraped top 100 songs to the created playlist.
- **Customization**: Allows users to specify the date and year for which they want to retrieve the top songs.
- **Error Handling**: Handles errors gracefully and provides informative error messages.

## Technologies Used

- **Python Libraries**:
  - `spotipy` for interacting with the Spotify Web API
  - `requests` for making HTTP requests
  - `datetime` for date manipulation
- **Spotify Web API**: Utilizes Spotify's API for retrieving song data and managing playlists.
- **OAuth 2.0**: Implements OAuth 2.0 authentication flow for accessing the user's Spotify account.

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/spotify-scraper.git`
2. Navigate to the project directory: `cd spotify-scraper`
3. Install dependencies: `pip install -r requirements.txt`
4. Register your application on the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/applications) to obtain client credentials.
5. Set up environment variables for your Spotify client ID and client secret:

```bash
export SPOTIPY_CLIENT_ID='your_client_id'
export SPOTIPY_CLIENT_SECRET='your_client_secret'
export SPOTIPY_REDIRECT_URI='your_redirect_uri'
```
## Usage

1. Run the main Python script: `python main.py`.
2. Follow the prompts to enter the date and year for which you want to retrieve the top 100 songs.
3. Log in to your Spotify account when prompted to authenticate the application.
4. The program will scrape the top 100 songs for the specified date and year and create a new playlist on your Spotify account.
5. Once the playlist is created, you can access it in your Spotify account and enjoy the top songs of that date and year.

