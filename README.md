# Free Spotify-Downloader

Download any playlist from your Spotify account as a .MP3 file using python and youtube.

This is a simple application allows you to download all your songs from Spotify. You can now listen to your songs without ads, just like at Spotify Premium

## WHAT YOU NEED:

- Python 3 or later
- Spotify account
- Spotify API credentials
- YouTube account
- IDE (ex: VS Code)

## How to Get started

1. download the repository zip file, and then extract the files.

2. Install the required dependencies using the following command in your terminal or command prompt:

```
pip install -r requirements.txt
```

3. Find your Spotify API credentials at [Spotify Dashboard](https://developer.spotify.com/dashboard/) and create a new app. Then, copy and paste the Client ID, Client Secret, and Redirect URL into a `.env` file in the root directory of the project like the following:

```
CLIENT_ID=<YOUR_CLIENT_ID>
CLIENT_SECRET=<YOUR_CLIENT_SECRET>
REDIRECT_URL=<YOUR_REDIRECT_URL>
```

4. Run the app

```
python main.py
```

### How to download a playlist

1. Select the folder where you want to save the downloaded songs.
2. Choose a playlist from your Spotify account that you want to download, then click on the "Download" button.
3. The app will search for the songs on YouTube and download them to the selected folder.
4. The songs will be saved in an MP3 format.
