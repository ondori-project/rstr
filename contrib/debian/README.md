
Debian
====================
This directory contains files used to package rstrd/rstr-qt
for Debian-based Linux systems. If you compile rstrd/rstr-qt yourself, there are some useful files here.

## rstr: URI support ##


rstr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rstr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rstrqt binary to `/usr/bin`
and the `../../share/pixmaps/rstr128.png` to `/usr/share/pixmaps`

rstr-qt.protocol (KDE)

