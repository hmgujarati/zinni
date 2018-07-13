
Debian
====================
This directory contains files used to package zinnid/zinni-qt
for Debian-based Linux systems. If you compile zinnid/zinni-qt yourself, there are some useful files here.

## zinni: URI support ##


zinni-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zinni-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zinniqt binary to `/usr/bin`
and the `../../share/pixmaps/zinni128.png` to `/usr/share/pixmaps`

zinni-qt.protocol (KDE)

