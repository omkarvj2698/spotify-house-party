# Spotify Collaborative Music App - "House Party"

## Overview
House Party is a full stack web application built using **Django** and **React.js**. It integrates the **Spotify API** to enable users to collaboratively manage music playback in real-time. Users can create or join rooms, set guest permissions, and vote to skip songs.

## Features
- **Collaborative Playback**: Users can join rooms and control Spotify playback together.
- **Room Permissions**: Customizable guest controls and voting system for song skipping.
- **Spotify API Integration**: Full control of playlists and playback through Spotify.

## Tech Stack
- **Frontend**: React.js, JavaScript
- **Backend**: Django, Python
- **Deployment**: Docker
- **Database**: SQLite (or MySQL)
- **Authentication**: Spotify OAuth 2.0


## Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/house-party.git

# Navigate to the project folder
cd house-party

# Backend setup
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver

# Frontend setup
cd frontend
npm run dev

