
Debian
====================
This directory contains files used to package insuranced/insurance-qt
for Debian-based Linux systems. If you compile insuranced/insurance-qt yourself, there are some useful files here.

## insurance: URI support ##


insurance-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install insurance-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your insuranceqt binary to `/usr/bin`
and the `../../share/pixmaps/insurance128.png` to `/usr/share/pixmaps`

insurance-qt.protocol (KDE)

