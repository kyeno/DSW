
Debian
====================
This directory contains files used to package petrolheadd/petrolhead-qt
for Debian-based Linux systems. If you compile petrolheadd/petrolhead-qt yourself, there are some useful files here.

## pivx: URI support ##


petrolhead-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install petrolhead-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your petrolhead-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

petrolhead-qt.protocol (KDE)

