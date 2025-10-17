<div align="center">
<img src="https://github.com/xiv3r/Termux-Desktop/blob/main/files/desktop.png">
</div>

# Requirements 
- [Termux APP](https://github.com/termux/termux-app/releases)
- [Termux X11](https://github.com/termux/termux-x11/releases)
- [Termux API](https://github.com/termux/termux-api/releases)

# Auto Install 
```
apt update && pkg upgrade -y && pkg install -y wget && clear && wget -q -O desktop.sh https://raw.githubusercontent.com/xiv3r/Termux-Desktop/refs/heads/main/files/desktop.sh && chmod 700 desktop.sh && bash desktop.sh
```

# Note
You can install any package from the termux terminal

e.g.
```
pkg update
pkg install chromium nano git -y
```
