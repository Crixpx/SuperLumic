
Debian
====================
This directory contains files used to package superlumicd/superlumic-qt
for Debian-based Linux systems. If you compile superlumicd/superlumic-qt yourself, there are some useful files here.

## superlumic: URI support ##


superlumic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install superlumic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your superlumic-qt binary to `/usr/bin`
and the `../../share/pixmaps/superlumic128.png` to `/usr/share/pixmaps`

superlumic-qt.protocol (KDE)

