# Midnight GTK Theme
Gtk2, Gtk3, Gtk4 and Gnome Shell theme based on [Midnight-Theme](https://github.com/i-mint/midnight) </br>
License : [GPLv3](https://choosealicense.com/licenses/gpl-3.0/)</br></br>
SCREENSHOTS:</br>
![midnightscreenshot](https://github.com/An-Eagle/midnight/assets/72992035/1f94cf0c-3aff-479f-9a53-38124d0b31b5)</br></br>
![midnightscreenshot](https://github.com/An-Eagle/midnight/assets/72992035/85436c16-8df2-4338-8e69-55d948f28356)</br>
# Installation
Clone the Midnight directory
```
git clone https://github.com/An-Eagle/midnight.git
```
for local use : </br>
```
mkdir .local/share/themes
cp -r midnight/Midnight ~/.local/share/themes/Midnight
cp -r midnight/gtk-4.0 ~/.config/gtk-4.0
```
for system-wide use : </br>
This is required to theme GDM </br>
```
sudo cp -r midnight/Midnight /usr/share/themes/Midnight
cp -r midnight/gtk-4.0 ~/.config/gtk-4.0
```
To enable, use [Gnome Tweaks](https://gitlab.gnome.org/GNOME/gnome-tweaks), in addition to the [User Themes Extensions](https://extensions.gnome.org/extension/19/user-themes/)
