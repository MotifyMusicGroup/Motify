
Debian
====================
This directory contains files used to package TNXd/TNX-qt
for Debian-based Linux systems. If you compile TNXd/TNX-qt yourself, there are some useful files here.

## TNX: URI support ##


TNX-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install TNX-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your TNXqt binary to `/usr/bin`
and the `../../share/pixmaps/TNX128.png` to `/usr/share/pixmaps`

TNX-qt.protocol (KDE)

