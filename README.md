# dmenu-externals

adds flatpak, appimagelauncher and snap apps to `dmenu_run`. requires `gio`.

apply to clean [dmenu 5.4](https://tools.suckless.org/dmenu/):

```sh
patch -p1 < /path/to/dmenu-externals-5.4.diff
sudo make install
```

[gpl-3.0-only](LICENSE). based on jwm's appimage launcher and
[suckless dmenu](https://tools.suckless.org/dmenu/); [upstream license](LICENSE.dmenu).
