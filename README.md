# 🎵 Billboard 100 to Spotify Playlist  

This project lets you **travel back in time** and create a private Spotify playlist of the *Billboard Hot 100* songs from any date you choose.  

---

## ✨ Features  
- 📊 Scrapes Billboard Hot 100 chart for a given date  
- 🔍 Searches the songs on Spotify  
- 🎶 Creates a private playlist in your Spotify account  
- ⚡ Adds all the available songs automatically  

---

## 📋 Requirements  
- Python 3.8+  
- Spotify Developer Account (for API credentials)  
- A `.env` file with your Spotify credentials  

---

## ⚙️ Installation  

1. **Clone this repo**  
   ```bash
   git clone https://github.com/your-username/billboard-to-spotify.git
   cd billboard-to-spotify

2. **Create a .env file in the root directory with your Spotify API credentials:**

    SPOTIPY_CLIENT_ID=your_client_id  
    SPOTIPY_CLIENT_SECRET=your_client_secret  
    SPOTIPY_REDIRECT_URI=http://127.0.0.1:8888/callback  

## 🚀 Usage
1. Run the script:
        python main.py
2. When prompted, enter a date in the format:
        YYYY-MM-DD
3. Example    
        Which year do you want to travel to? Type the date in this format YYYY-MM-DD: 2000-08-12

## 📌 Example Output
        2000-08-12 Billboard 100
        Playlist created successfully!
        Skipped: Some unavailable tracks

## 📦 Dependencies

    spotipy

    BeautifulSoup4

    requests

    python-dotenv

## Install them with:
        pip install spotipy beautifulsoup4 requests python-dotenv


## ⚠️ Notes

### Your Redirect URI must be added in the Spotify Developer Dashboard

        Example:

        http://127.0.0.1:8888/callback