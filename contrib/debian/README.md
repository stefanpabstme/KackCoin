
Debian
====================
This directory contains files used to package kckd/kck-qt
for Debian-based Linux systems. If you compile kckd/kck-qt yourself, there are some useful files here.

## kck: URI support ##


kck-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kck-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kckqt binary to `/usr/bin`
and the `../../share/pixmaps/kck128.png` to `/usr/share/pixmaps`

kck-qt.protocol (KDE)

