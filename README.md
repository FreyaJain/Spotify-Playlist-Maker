# Spotify Playlist Maker - Content-Based Recommendation System

## Overview
This project is a Spotify playlist maker that utilizes a content-based recommendation system built using Python. It leverages the Spotify API to access user data, including playlists, artists, and song history. The system analyzes the user's playlist preferences and generates custom playlists based on their song choices.

## Features
- Accesses Spotify API to retrieve user data
- Analyzes user playlists and song preferences
- Generates custom playlists using a content-based recommendation system
- Provides a user-friendly interface for interaction

## Requirements
- Python 3.x
- Spotify Developer Account (for API access)
- Required Python packages (install using `pip install -r requirements.txt`):
  - spotipy
  - pandas
  - scikit-learn (or other relevant machine learning libraries)

## Setup
1. Clone the repository:
    ```bash
   git clone https://github.com/FreyaJain/spotify-playlist-maker.git
   cd spotify-playlist-maker
    
2. Obtain Spotify API credentials:
   Create a Spotify Developer Account and create a new application.
   Copy the client ID and client secret.
   
3. Set up environment variables:
   Create a .env file in the project root.
   Add the following lines to the .env file:
   SPOTIPY_CLIENT_ID=your_spotify_client_id
   SPOTIPY_CLIENT_SECRET=your_spotify_client_secret
   SPOTIPY_REDIRECT_URI=http://localhost:8888/callback  # Change the redirect URI as needed

4. Run the application:
   python app.py

