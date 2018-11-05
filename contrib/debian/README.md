
Debian
====================
This directory contains files used to package ingenuityd/ingenuity-qt
for Debian-based Linux systems. If you compile ingenuityd/ingenuity-qt yourself, there are some useful files here.

## ingenuity: URI support ##


ingenuity-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ingenuity-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ingenuityqt binary to `/usr/bin`
and the `../../share/pixmaps/ingenuity128.png` to `/usr/share/pixmaps`

ingenuity-qt.protocol (KDE)

