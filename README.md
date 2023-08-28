# JioTVServer

Grab streaming links of JioTV channels and play on mobile, PC etc..

NOTE: It only works in Indian VPS due to geoblocking

## Features
- Free of cost :)
- Easy to set-up and use
- High Quality Streaming
- Fast 🔥

## Installation

### Android/Termux
<details>
  <summary>Click to expand!</summary>

```bash
# Upgrade system packages
pkg update && pkg upgrade
```
```bash
# Get 'git' and 'PHP'
pkg install git php
```
```bash
# Download script
git clone https://github.com/danishansari04/jiotv
```
```bash
# Run the script
php -S localhost:8585 -t "$HOME/jiotv"
```
</details>

## Usage

- [For first time users] Generate credentials using your Jio phone number and password.

  <details>
    
  Open your web browser and put the URL as follows
  FIRSTLY GO AND LOGIN YOUR ID FOLLOW THIS LINK
  ```
  Format: http://localhost:8585/app/login.php
  ```
  </details>

- For Web Play, the URL is: `http://localhost:8585`
- For IPTV Players (OTT Navigator or TiviMate), the playlist URL is: `http://localhost:8585/playlist.php`



