# xdg-desktop-portal-hyprland With GTK
An [XDG Desktop Portal](https://github.com/flatpak/xdg-desktop-portal) backend for Hyprland.

## Installing
```sh
git clone -b theoparis/fix-build --recursive https://github.com/dragontos/xdg-desktop-portal-hyprland
cd xdg-desktop-portal-hyprland/
make all
sudo make install
```
## Make all
```sh
make all
sudo make install
```
## Make hyprland-share-picker
```
meson build
ninja -C build
```

## Running, FAQs, etc.
See [the Hyprland wiki](https://wiki.hyprland.org/Useful-Utilities/Hyprland-desktop-portal/)

