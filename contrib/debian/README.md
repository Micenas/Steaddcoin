
Debian
====================
This directory contains files used to package gormintd/gormint-qt
for Debian-based Linux systems. If you compile gormintd/gormint-qt yourself, there are some useful files here.

## gormint: URI support ##


gormint-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gormint-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gormintqt binary to `/usr/bin`
and the `../../share/pixmaps/gormint128.png` to `/usr/share/pixmaps`

gormint-qt.protocol (KDE)

