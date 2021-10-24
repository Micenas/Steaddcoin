
Debian
====================
This directory contains files used to package steaddcoind/steaddcoin-qt
for Debian-based Linux systems. If you compile steaddcoind/steaddcoin-qt yourself, there are some useful files here.

## steaddcoin: URI support ##


steaddcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install steaddcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your steaddcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/steaddcoin128.png` to `/usr/share/pixmaps`

steaddcoin-qt.protocol (KDE)

