
Debian
====================
This directory contains files used to package pruxd/prux-qt
for Debian-based Linux systems. If you compile pruxd/prux-qt yourself, there are some useful files here.

## prux: URI support ##


prux-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install prux-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your prux-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

prux-qt.protocol (KDE)

