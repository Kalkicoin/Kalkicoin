
Debian
====================
This directory contains files used to package kalkicoind/kalkicoin-qt
for Debian-based Linux systems. If you compile kalkicoind/kalkicoin-qt yourself, there are some useful files here.

## kalkicoin: URI support ##


kalkicoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install kalkicoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your kalkicoinqt binary to `/usr/bin`
and the `../../share/pixmaps/kalkicoin128.png` to `/usr/share/pixmaps`

kalkicoin-qt.protocol (KDE)

