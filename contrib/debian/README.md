
Debian
====================
This directory contains files used to package othilad/othila-qt
for Debian-based Linux systems. If you compile othilad/othila-qt yourself, there are some useful files here.

## othila: URI support ##


othila-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install othila-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your othilaqt binary to `/usr/bin`
and the `../../share/pixmaps/othila128.png` to `/usr/share/pixmaps`

othila-qt.protocol (KDE)

