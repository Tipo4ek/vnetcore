
Debian
====================
This directory contains files used to package vnetd/vnet-qt
for Debian-based Linux systems. If you compile vnetd/vnet-qt yourself, there are some useful files here.

## vnet: URI support ##


vnet-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vnet-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vnet-qt binary to `/usr/bin`
and the `../../share/pixmaps/vnet128.png` to `/usr/share/pixmaps`

vnet-qt.protocol (KDE)

