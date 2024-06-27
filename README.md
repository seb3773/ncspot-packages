# ncspot-packages
Debian bookworm packages for ncspot  
  
++ncspot:  
ncspot is an ncurses Spotify client written in Rust using librespot. It is heavily inspired by ncurses MPD clients, such as ncmpc.  
ncspot only works with a Spotify premium account as it offers features that are not available for free accounts.  
  
Features:  
Support for tracks, albums, playlists, genres, searching...  
Small resource footprint  
Support for a lot of platforms  
Vim keybindings out of the box  
IPC socket for remote control  
Automatic authentication using a password manager  
  
https://github.com/hrkfdn/ncspot  
+-------------------------------------------------  
  
I builded these packages because they are not in debian 12 repository; and I don't want to use infamous snap version or flatpak... 

x64,i386 & armhf packages provided.  
  
# installation:  
  
download appropriate package, and do (for example for 32bits package):  
  
```
sudo apt install ./ncspot-1.1.1_i386.deb
```
(or install with graphical .deb installer if you have one, for example QSI installer for q4os: left click the .deb, then 'open with' and choose QSI installer)  
  
The package takes care of creating the corresponding '.desktop' entry (so you will have access to ncspot from your applications menu).  
  
+---+  

