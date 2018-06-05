
Debian
====================
This directory contains files used to package bitsliverd/bitsliver-qt
for Debian-based Linux systems. If you compile bitsliverd/bitsliver-qt yourself, there are some useful files here.

## bitsliver: URI support ##


bitsliver-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitsliver-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitsliverqt binary to `/usr/bin`
and the `../../share/pixmaps/bitsliver128.png` to `/usr/share/pixmaps`

bitsliver-qt.protocol (KDE)

