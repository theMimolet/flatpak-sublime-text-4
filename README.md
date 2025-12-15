# Sublime Text 4 as Flatpak

![Sublime Text working fine in KDE](https://github.com/theMimolet/com.sublimehq.SublimeText/blob/main/screenshots/screenshot-kde.png)

This repo only serves as testing grounds before making any Pull Requests to Flathub

Most of the work has already been done by ptomato, ryanpcmcquen, hfiguiere and barthalion - and credit is due for their work.

## The repo

There is a repo made for **testing purposes** and might not be ready for production just yet !
Your feedback is important !

It can be taken down at any time if there are any issues with it existing.

Here are the commands to install it :
```sh
flatpak remote-add --user --no-gpg-verify st4-testing https://themimolet.github.io/com.sublimehq.SublimeText/
flatpak install st4-testing com.sublimehq.SublimeText
flatpak run com.sublimehq.SublimeText
```