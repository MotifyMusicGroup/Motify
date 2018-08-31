
Debian
====================
This directory contains files used to package MDFYd/MDFY-qt
for Debian-based Linux systems. If you compile MDFYd/MDFY-qt yourself, there are some useful files here.

## MDFY: URI support ##


MDFY-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install MDFY-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your MDFYqt binary to `/usr/bin`
and the `../../share/pixmaps/MDFY128.png` to `/usr/share/pixmaps`

MDFY-qt.protocol (KDE)

