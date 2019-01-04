
Debian
====================
This directory contains files used to package salvaged/salvage-qt
for Debian-based Linux systems. If you compile salvaged/salvage-qt yourself, there are some useful files here.

## salvage: URI support ##


salvage-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install salvage-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your salvageqt binary to `/usr/bin`
and the `../../share/pixmaps/salvage128.png` to `/usr/share/pixmaps`

salvage-qt.protocol (KDE)

