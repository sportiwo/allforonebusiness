
Debian
====================
This directory contains files used to package allforonebusinessd/allforonebusiness-qt
for Debian-based Linux systems. If you compile allforonebusinessd/allforonebusiness-qt yourself, there are some useful files here.

## allforonebusiness: URI support ##


allforonebusiness-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install allforonebusiness-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your allforonebusiness-qt binary to `/usr/bin`
and the `../../share/pixmaps/allforonebusiness128.png` to `/usr/share/pixmaps`

allforonebusiness-qt.protocol (KDE)

