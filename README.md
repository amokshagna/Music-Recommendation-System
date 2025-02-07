# Music-Recommendation-System
Music Recommender System

Overview

This is a Music Recommender System built using Streamlit, Spotipy, and Pickle. The application suggests songs based on a selected track and displays the album covers using the Spotify API.

Features

Select a song from a dropdown list

Get five recommended songs based on similarity

Display the album cover of each recommended song

Interactive UI using Streamlit

Technologies Used

Python

Streamlit (for UI)

Spotipy (for fetching album cover images)

Pickle (for loading precomputed song similarity data)

Installation

Prerequisites

Ensure you have Python 3.x installed.

Clone the Repository

git clone https://github.com/your-username/music-recommender.git
cd music-recommender

Install Dependencies

pip install -r requirements.txt

Running the Application

streamlit run app.py

Project Structure

.
├── app.py  # Main application script
├── df.pkl  # Pickled dataset containing songs and metadata
├── similarity.pkl  # Pickled similarity matrix
├── requirements.txt  # Dependencies list
├── README.md  # Project documentation

Environment Variables

Create a .env file and add your Spotify API credentials:

SPOTIPY_CLIENT_ID=your_client_id
SPOTIPY_CLIENT_SECRET=your_client_secret

Author

Your Name

License

This project is licensed under the MIT License.

