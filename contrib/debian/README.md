
Debian
====================
This directory contains files used to package DUELIUMd/DUELIUM-qt
for Debian-based Linux systems. If you compile DUELIUMd/DUELIUM-qt yourself, there are some useful files here.

## DUELIUM: URI support ##


DUELIUM-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install DUELIUM-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your DUELIUMqt binary to `/usr/bin`
and the `../../share/pixmaps/DUELIUM128.png` to `/usr/share/pixmaps`

DUELIUM-qt.protocol (KDE)

