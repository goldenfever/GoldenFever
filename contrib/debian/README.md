
Debian
====================
This directory contains files used to package gfrd/gfr-qt
for Debian-based Linux systems. If you compile gfrd/gfr-qt yourself, there are some useful files here.

## gfr: URI support ##


gfr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gfr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gfrqt binary to `/usr/bin`
and the `../../share/pixmaps/gfr128.png` to `/usr/share/pixmaps`

gfr-qt.protocol (KDE)

