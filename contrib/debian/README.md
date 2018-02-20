
Debian
====================
This directory contains files used to package neodashd/neodash-qt
for Debian-based Linux systems. If you compile neodashd/neodash-qt yourself, there are some useful files here.

## neodash: URI support ##


neodash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install neodash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your neodash-qt binary to `/usr/bin`
and the `../../share/pixmaps/neodash128.png` to `/usr/share/pixmaps`

neodash-qt.protocol (KDE)
