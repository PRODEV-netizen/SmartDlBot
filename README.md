<h1 align="center">SmartDlBot Telegram Bot 🌌</h1>

<p align="center">
  <em>SmartDlBot: The ultimate toolkit on Telegram, offering Facebook,YouTube,Pinterest,Spotify Downloader. Simplify your tasks with ease!</em>
</p>

<p align="center">
  <a href="https://github.com/abirxdhack/SmartDlBot/stargazers"><img alt="GitHub stars" src="https://img.shields.io/github/stars/abirxdhack/SmartDlBot"></a>
  <a href="https://github.com/abirxdhack/SmartDlBot/network/members"><img alt="GitHub forks" src="https://img.shields.io/github/forks/abirxdhack/SmartDlBot"></a>
  <a href="https://github.com/abirxdhack/SmartDlBot/issues"><img alt="GitHub issues" src="https://img.shields.io/github/issues/abirxdhack/SmartDlBot"></a>
  <a href="https://github.com/abirxdhack/SmartDlBot/pulls"><img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/abirxdhack/SmartDlBot"></a>
  <img alt="PyPI - Python Version" src="https://img.shields.io/pypi/pyversions/pyrogram">
</p>

<hr>

## 🌟 Features

- **Facebook Video Downloader**: Download videos from Facebook.
- **YouTube Video Downloader**: Download videos from YouTube.
- **Pinterest Video Downloader**: Download videos from Pinterest.
- **Spotify Track Downloader**: Download tracks from Spotify.
- **Instagram Reel Downloader**: Download Reels From Instagram
- **TikTok Video Downloader**: Download TikTok Video From TikTok  

## Installation

To install `pyrogram` , `yt-dlp` , `spotipy` , `requests` , `pillow` , `asyncio` , `aiofiles` , `aiohttp`  run the following command:

```bash
pip install -r requirements.txt
```

**Note: If you previously installed `pyrofork`, uninstall it before installing `pyrogram`.**

## Handling YouTube Download Errors with Cookies

To avoid errors related to YouTube sign-in requirements, using a cookie file is effective. Here's how to set it up:

### Steps to Export and Use Cookies:

1. **Create a Dedicated Chrome Profile:**
   - It's recommended to create a new Chrome profile for managing your bot's cookies.

2. **Install a Cookie Management Extension:**
   - Use [Cookie Editor](https://chromewebstore.google.com/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm) or similar extensions to manage your cookies.

3. **Export Cookies from YouTube:**
   - Log into YouTube in your new browser profile and export cookies in Netscape format via the cookie extension.

4. **Save the Cookies File:**
   - Update your `cookies.txt` in the `SmartDlBot/cookies` directory of your project.

### Managing Cookies:

- **Cookie Expiry:**
  - Refresh your cookies by exporting new ones if you encounter download issues.

- **Cookie Depletion:**
  - Avoid frequent bot restarts and excessive YouTube requests to prevent early cookie expiry.

This setup should help manage YouTube content access efficiently without encountering sign-in or bot protection errors.

## Configuration

1. Open the `config.py` file in your favorite text editor.
2. Replace the placeholders for `API_ID`, `API_HASH`,  `BOT_TOKEN`, `SPOTIFY_CLIENT_ID`, and `SPOTIFY_CLIENT_SECRET` with your actual values:
   - **`API_ID`**: Your API ID from [my.telegram.org](https://my.telegram.org).
   - **`API_HASH`**: Your API Hash from [my.telegram.org](https://my.telegram.org).
   - **`BOT_TOKEN`**: The token you obtained from [@BotFather](https://t.me/BotFather).
   - **`SPOTIFY_CLIENT_ID`**: SPOTIFY_CLIENT_ID from [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
   - **`SPOTIFY_CLIENT_SECRET`**: SPOTIFY_CLIENT_SECRET from [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
   - **`MONGO_URL`**: MONGO_URL from [MONGODB DATABASE](http://mongodb.com/)  

## Deploy the Bot

```sh
git clone https://github.com/abirxdhack/SmartDlBot
cd SmartDlBot
python3 main.py
```

## Deploy the Bot With Screen

```sh
git clone https://github.com/abirxdhack/SmartDlBot
cd SmartDlBot
screen -S SmartDlBot
python3 main.py
```

## Usage 🛠️

The bot supports the following commands:

Download videos and tracks from popular platforms using these commands:

➢ **`/fb [Video URL]`** - Download a Facebook video.
   - Example: **/fb https://www.facebook.com/share/v/18VH1yNXoq/** **`Downloads the specified Facebook video`**
   - Note: Private Facebook videos cannot be downloaded.

➢ **`/pin [Video URL]`** - Download a Pinterest video.
   - Example: **/pin https://pin.it/6GoDMRwmE** **`Downloads the specified Pinterest video`**

➢ **`/in [Video URL]`** - Download a Instagram video.
   - Example: **/in https://www.instagram.com/reel/C_vOYErJBm7/?igsh=YzljYTk1ODg3Zg== ** **`Downloads the specified Instagram video`**
     
➢ **`/tt [Video URL]`** - Download a TikTok Video.
   - Example: **/tt https://vt.tiktok.com/ZSMV19Kfu/** **`Downloads the specified TikTok Video**`     

➢ **`/sp [Track URL]`** - Download a Spotify track.
   - Example: **/sp https://open.spotify.com/track/7ouBSPZKQpm7zQz2leJXta** **`Downloads the specified Spotify track**`

➢ **`/yt [Video URL]`** - Download a YouTube video.
   - Example: **/yt https://youtu.be/In8bfGnXavw** **`Downloads the specified YouTube video`**

➢ **`/song [Video URL]`** - Download a YouTube video as an MP3 file.
   - Example: **/song https://youtu.be/In8bfGnXavw** **`Converts and downloads the video as MP3`**

**Or You Can Use Below Commands **

➢ **`.fb [Video URL]`** - Download a Facebook video.
   - Example: **.fb https://www.facebook.com/share/v/18VH1yNXoq/** **`Downloads the specified Facebook video`**
   - Note: Private Facebook videos cannot be downloaded.

➢ **`.pin [Video URL]`** - Download a Pinterest video.
   - Example: **.pin https://pin.it/6GoDMRwmE** **`Downloads the specified Pinterest video`**
   - Note: 18+ Instagram Reels cannot be downloaded.
     
➢ **`.in [Video URL]`** - Download a Instagram video.
   - Example: **/in https://www.instagram.com/reel/C_vOYErJBm7/?igsh=YzljYTk1ODg3Zg== ** **`Downloads the specified Instagram video`**
     
➢ **`.tt [Video URL]`** - Download a TikTok Video.
   - Example: **/tt https://vt.tiktok.com/ZSMV19Kfu/** **`Downloads the specified TikTok Video**`     

➢ **`.sp [Track URL]`** - Download a Spotify track.
   - Example: **.sp https://open.spotify.com/track/7ouBSPZKQpm7zQz2leJXta** **`Downloads the specified Spotify track`**

➢ **`.yt [Video URL]`** - Download a YouTube video.
   - Example: **.yt https://youtu.be/In8bfGnXavw** **`Downloads the specified YouTube video`**

➢ **`.song [Video URL]`** - Download a YouTube video as an MP3 file.
   - Example: **.song https://youtu.be/In8bfGnXavw** **`Converts and downloads the video as MP3`**

## NOTE
**Provide a valid public URL for each platform to download successfully**
For inquiries or feedback, please feel free to reach out via Telegram.

## Ethical Notice 🔔
> **Ethics Reminder:** Simply modifying a few lines of code does not constitute original authorship. When forking a project, always fork responsibly and give proper credit to the original creators.

# Project Contributors

## Author 📝

- Name: Abir Arafat Chawdhury
- Telegram: [@abirxdhackz](https://t.me/abirxdhackz)

## Update Author
- Name ᔰ ᦲ ᔰ 「🇲🇲」
- Telegram: [@nkka404](https://t.me/nkka404)
