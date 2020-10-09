# jrommanager-gentoo
Gentoo Overlay for JRomManager

To use this overlay:
1. Add overlay (only the first time): `layman -o https://raw.githubusercontent.com/bugalo/jrommanager-gentoo/master/overlay.xml -f -a jrommanager`
2. Sync the overlay: `layman -s jrommanager`
3. If you use eix then do `eix-update`
4. Install/update with `emerge -av jrommanager`
