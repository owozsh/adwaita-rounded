# Adwaita Rounded

Just a patch to make the bottom corners rounded. (and add some padding to the gnome-terminal too ;).

![screenshot](./screenshot.png)

### Some information

- Make sure to use the default background colors for your gnome-terminal.
- This 'patch' is a workaround, the corners must be fixed at the core of programs (as far as I know).
- Since this is a workaround, I don't recommend it for everyone, just people who really dislikes the square corners and use the default Adwaita theme, without tweaks.

### How to install

Just run the install.sh script

```
git clone https://github.com/owozsh/adwaita-rounded.git
cd adwaita-rounded
./install.sh
```

To uninstall, just remove the gtk.css file from your ~/.config/gtk-3.0/.
