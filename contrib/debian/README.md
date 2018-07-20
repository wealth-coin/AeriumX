
Debian
====================
This directory contains files used to package wealthsilod/wealthsilo-qt
for Debian-based Linux systems. If you compile wealthsilod/wealthsilo-qt yourself, there are some useful files here.

## wealthsilo: URI support ##


wealthsilo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install wealthsilo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your wealthsiloqt binary to `/usr/bin`
and the `../../share/pixmaps/wealthsilo128.png` to `/usr/share/pixmaps`

wealthsilo-qt.protocol (KDE)

