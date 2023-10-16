# vlc-youtubeDL
A vlc addon for [yt-dlp](https://github.com/yt-dlp/yt-dlp) integration.

### Prerequisites
- A working `yt-dlp` installation (`yt-dlp` must be in `$PATH`)

### Installation
Put [`yt-dlp.lua`](https://github.com/robturner45/vlc-yt-dlp/blob/master/yt-dlp.lua) into:
- In Windows: `%APPDATA%\vlc\lua\playlist\`
- In Mac OS X: `/Users/%your_name%/Library/Application Support/org.videolan.vlc/lua/playlist/`
- In Linux: `~/.local/share/vlc/lua/playlist/`

### Usage
Simply open a YouTube link in VLC. You will not be able to seek so if you want to start at a particular time set that in vlc when you are at the "open network stream" window.

This is a simple fork of mjasny's vlc-youtube-dl plugin for vlc [found here](https://github.com/mjasny/vlc-youtubeDL)
Thank you to them. All I did was change it to work with yt-dlp
