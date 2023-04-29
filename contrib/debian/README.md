
Debian
====================
This directory contains files used to package zdokd/zdok-qt
for Debian-based Linux systems. If you compile zdokd/zdok-qt yourself, there are some useful files here.

## zdok: URI support ##


zdok-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zdok-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zdok-qt binary to `/usr/bin`
and the `../../share/pixmaps/zdok128.png` to `/usr/share/pixmaps`

zdok-qt.protocol (KDE)

