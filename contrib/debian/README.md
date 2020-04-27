
Debian
====================
This directory contains files used to package cryptowithacaused/cryptowithacause-qt
for Debian-based Linux systems. If you compile cryptowithacaused/cryptowithacause-qt yourself, there are some useful files here.

## cryptowithacause: URI support ##


cryptowithacause-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptowithacause-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptowithacause-qt binary to `/usr/bin`
and the `../../share/pixmaps/cryptowithacause128.png` to `/usr/share/pixmaps`

cryptowithacause-qt.protocol (KDE)

