
Debian
====================
This directory contains files used to package deliverycoind/deliverycoin-qt
for Debian-based Linux systems. If you compile deliverycoind/deliverycoin-qt yourself, there are some useful files here.

## deliverycoin: URI support ##


deliverycoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install deliverycoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your deliverycoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

deliverycoin-qt.protocol (KDE)

