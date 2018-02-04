
Debian
====================
This directory contains files used to package cupcoind/cupcoin-qt
for Debian-based Linux systems. If you compile cupcoind/cupcoin-qt yourself, there are some useful files here.

## cupcoin: URI support ##


cupcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cupcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cupcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/cupcoin128.png` to `/usr/share/pixmaps`

cupcoin-qt.protocol (KDE)

