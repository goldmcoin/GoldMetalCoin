
Debian
====================
This directory contains files used to package goldmetalcoind/goldmetalcoin-qt
for Debian-based Linux systems. If you compile goldmetalcoind/goldmetalcoin-qt yourself, there are some useful files here.

## goldmetalcoin: URI support ##


goldmetalcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install goldmetalcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your goldmetalcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/goldmetalcoin128.png` to `/usr/share/pixmaps`

goldmetalcoin-qt.protocol (KDE)

