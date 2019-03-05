
Debian
====================
This directory contains files used to package peepcoin2d/peepcoin2-qt
for Debian-based Linux systems. If you compile peepcoin2d/peepcoin2-qt yourself, there are some useful files here.

## peepcoin2: URI support ##


peepcoin2-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install peepcoin2-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your peepcoin2qt binary to `/usr/bin`
and the `../../share/pixmaps/peepcoin2128.png` to `/usr/share/pixmaps`

peepcoin2-qt.protocol (KDE)

