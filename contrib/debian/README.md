
Debian
====================
This directory contains files used to package ensuranced/ensurance-qt
for Debian-based Linux systems. If you compile ensuranced/ensurance-qt yourself, there are some useful files here.

## ensurance: URI support ##


ensurance-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ensurance-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ensuranceqt binary to `/usr/bin`
and the `../../share/pixmaps/ensurance128.png` to `/usr/share/pixmaps`

ensurance-qt.protocol (KDE)

