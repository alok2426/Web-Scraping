# 🎵 Spotify API Analysis (Search Query Based)

This project demonstrates how to use the **Spotify Web API** (via the Spotipy library) to search for **tracks, albums, artists, and playlists** based on a given query and export the results into an **Excel file**.

## 📂 Project Files
- **Spotify API Analysis Search Query Based.PY.py**: The main Python script that fetches data from the Spotify API.
- **Spotify_Kabir_Singh.xlsx**: The output Excel file containing data fetched from Spotify for the query **"Kabir Singh"**.

---

## 🚀 Features
- Search Spotify by **track, album, artist, or playlist**.
- Retrieve details such as **name, artist, release date, popularity, followers, duration**, and more.
- Convert track durations from milliseconds to a readable format (mm:ss).
- Export the collected data into a well-structured **Excel file** with multiple sheets.

---

## 🛠️ Requirements
Ensure you have the following libraries installed:
```bash
pip install spotipy pandas openpyxl
