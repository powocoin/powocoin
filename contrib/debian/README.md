
Debian
====================
This directory contains files used to package powocoind/powocoin-qt
for Debian-based Linux systems. If you compile powocoind/powocoin-qt yourself, there are some useful files here.

## powocoin: URI support ##


powocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install powocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your powocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/powocoin128.png` to `/usr/share/pixmaps`

powocoin-qt.protocol (KDE)

