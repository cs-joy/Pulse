
Debian
====================
This directory contains files used to package pulsed/pulse-qt
for Debian-based Linux systems. If you compile pulsed/pulse-qt yourself, there are some useful files here.

## pulse: URI support ##


pulse-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pulse-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pulse-qt binary to `/usr/bin`
and the `../../share/pixmaps/pulse128.png` to `/usr/share/pixmaps`

pulse-qt.protocol (KDE)
