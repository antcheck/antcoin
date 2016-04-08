
Debian
====================
This directory contains files used to package antcoind/antcoin-qt
for Debian-based Linux systems. If you compile antcoind/antcoin-qt yourself, there are some useful files here.

## antcoin: URI support ##


antcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install antcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your antcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/antcoin128.png` to `/usr/share/pixmaps`

antcoin-qt.protocol (KDE)

