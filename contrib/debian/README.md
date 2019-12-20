
Debian
====================
This directory contains files used to package masterwind/masterwin-qt
for Debian-based Linux systems. If you compile masterwind/masterwin-qt yourself, there are some useful files here.

## masterwin: URI support ##


masterwin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install masterwin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your masterwinqt binary to `/usr/bin`
and the `../../share/pixmaps/masterwin128.png` to `/usr/share/pixmaps`

masterwin-qt.protocol (KDE)

