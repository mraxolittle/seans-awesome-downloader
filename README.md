🎬 seans-awesome-downloader
A powerful and easy-to-use video & audio downloader supporting all major websites.

Currently supports:

YouTube, YouTube Music, Dropout, Twitch, Snapchat, SoundCloud, all major adult sites (for the gooners among us 👀), Bilibili, Paramount, Patreon, Pinterest, PeerTube, PBS, RTÉ, South Park, TikTok, Twitter (X – The Everything App!), Vimeo, Zoom.

More to come, of course! 🚀

✅ How to Use
Open urls.txt

Paste one video or playlist URL per line

Save the file

Double-click the batch file for your desired format:

🎥 Video Download Options
Batch File	Description

download-360p.bat	- Downloads video(s) in 360p

download-512p.bat	- Downloads video(s) in 512p

download-720p.bat	- Downloads video(s) in 720p

download-video.bat - Downloads the best available video quality

🎵 Audio Download Options

Batch File - Description

download-audio.bat - Downloads audio as MP3

download-audio-wav.bat - Downloads audio as WAV

🗂️ Downloaded files will be saved in their respective folders (mp4s/, mp3s/, wav/, etc.).

🎛️ Advanced Usage (Custom Downloads)
Want full control? Use the command line!

Open Command Prompt
Press Win + R, type cmd, and hit Enter.

Drag yt-dlp.exe into the terminal window.

Type your custom command.

🔧 Examples:
Download best video + audio and merge:
yt-dlp.exe -f bestvideo+bestaudio --merge-output-format mp4 https://www.youtube.com/watch?v=VIDEO_ID

Download audio as MP3:
yt-dlp.exe -x --audio-format mp3 https://www.youtube.com/watch?v=VIDEO_ID

Download subtitles (English):
yt-dlp.exe --write-subs --sub-lang en https://www.youtube.com/watch?v=VIDEO_ID

Set custom output filename:
yt-dlp.exe -o "downloads/%(title)s.%(ext)s" https://www.youtube.com/watch?v=VIDEO_ID

Skip already downloaded files (using archive):
yt-dlp.exe --download-archive archive.txt https://www.youtube.com/playlist?list=PLAYLIST_ID

List all available formats:
yt-dlp.exe -F https://www.youtube.com/watch?v=VIDEO_ID

⚠️ Reminder
Use responsibly - many videos are copyrighted.

🎨 Support creators when they deserve it.

Otherwise...

Happy pirating! 🏴‍☠️
