
Debian
====================
This directory contains files used to package patd/pat-qt
for Debian-based Linux systems. If you compile patd/pat-qt yourself, there are some useful files here.

## pat: URI support ##


pat-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pat-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your patqt binary to `/usr/bin`
and the `../../share/pixmaps/pat128.png` to `/usr/share/pixmaps`

pat-qt.protocol (KDE)

