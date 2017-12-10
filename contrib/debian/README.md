
Debian
====================
This directory contains files used to package mgnd/mgn-qt
for Debian-based Linux systems. If you compile mgnd/mgn-qt yourself, there are some useful files here.

## mgn: URI support ##


mgn-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mgn-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your mgnqt binary to `/usr/bin`
and the `../../share/pixmaps/mgn128.png` to `/usr/share/pixmaps`

mgn-qt.protocol (KDE)

