# seans-awesome-downloader
A powerful and easy-to-use video &amp; audio downloader supporting all major websites.

Currently supports Youtube, Youtube Music, Dropout, Twitch, Snapchat, Soundcloud, All Major Porn sites (For the gooners among us), Bilibili, Paramount, Patreon, Pinterest, Peertube, PBS, RTE, Southpark, Tiktok, Twitter(X THE EVERYTHING APP!!!), Vimeo, Zoom.

# With more to come ofcourse!

✅ How to Use

Open urls.txt
Paste the URL of the video or playlist you want to download.
One URL per line (you can paste multiple).
Save the file.
Choose the batch file for your desired format and quality:

🟢 download-360p.bat → Downloads video(s) in 360p.
🟢 download-512p.bat → Downloads video(s) in 512p.
🟢 download-720p.bat → Downloads video(s) in 720p.
🟢 download-video.bat → Downloads the best available video quality.
🎵 download-audio.bat → Downloads audio only (MP3).
🎵 download-audio-wav.bat → Downloads audio as WAV.

Double-click the batch file.
The download will start automatically.
Files will be saved in their respective folders (mp4s, mp3s, wav, etc.).

🎛️ Custom Downloads (Advanced)
If you want full control over what you download:
Open Command Prompt (cmd).
Drag yt-dlp.exe into the terminal window.
Type or paste your custom command.
Examples of what you can do:

✅ Download best video + audio and merge:
yt-dlp.exe -f bestvideo+bestaudio --merge-output-format mp4 https://www.youtube.com/watch?v=VIDEO_ID

✅ Download audio as MP3:
yt-dlp.exe -x --audio-format mp3 https://www.youtube.com/watch?v=VIDEO_ID

✅ Download subtitles:
yt-dlp.exe --write-subs --sub-lang en https://www.youtube.com/watch?v=VIDEO_ID

✅ Set custom output filename:
yt-dlp.exe -o "downloads/%(title)s.%(ext)s" https://www.youtube.com/watch?v=VIDEO_ID

✅ Skip already downloaded files (using archive):
yt-dlp.exe --download-archive archive.txt https://www.youtube.com/playlist?list=PLAYLIST_ID

✅ List all available formats before downloading:
yt-dlp.exe -F https://www.youtube.com/watch?v=VIDEO_ID



⚠️ Reminder:
Use responsibly—many videos are copyrighted. Support creators when they deserve it, OTHERWISE:

Happy pirating! 🏴‍☠️
