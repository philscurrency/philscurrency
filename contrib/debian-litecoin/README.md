
Debian
====================
This directory contains files used to package philscurrencyd/philscurrency-qt
for Debian-based Linux systems. If you compile philscurrencyd/philscurrency-qt yourself, there are some useful files here.

## philscurrency: URI support ##


philscurrency-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install philscurrency-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your philscurrency-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

philscurrency-qt.protocol (KDE)

