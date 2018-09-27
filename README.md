# jrommanager-gentoo
Gentoo Overlay for JRomManager

To use this overlay:
1. Add overlay (only the first time): `layman -o https://raw.githubusercontent.com/optyfr/jrommanager-gentoo/master/overlay.xml -f -a jrommanager`
2. Sync the overlay: `layman -s jrommanager`
3. Only if you use eix: `eix-update`
4. Install with `emerge -v jrommanager` or update with `emerge -uv jrommanager`
