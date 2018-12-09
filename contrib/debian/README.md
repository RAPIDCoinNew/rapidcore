
Debian
====================
This directory contains files used to package rapidd/rapid-qt
for Debian-based Linux systems. If you compile rapidd/rapid-qt yourself, there are some useful files here.

## rapid: URI support ##


rapid-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rapid-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rapid-qt binary to `/usr/bin`
and the `../../share/pixmaps/rapid128.png` to `/usr/share/pixmaps`

rapid-qt.protocol (KDE)

