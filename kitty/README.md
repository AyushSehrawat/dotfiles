# Kitty

Consider this folder as `~/.config/kitty`

## Installation and setting up Kitty

#### Installation of kitty

```
curl -L https://sw.kovidgoyal.net/kitty/installer.sh | sh /dev/stdin launch=n
```

#### Adding to path

```
sudo ln -s ~/.local/kitty.app/bin/kitty /usr/local/bin/
```

#### Making it available in application launcher

```
cp ~/.local/kitty.app/share/applications/kitty.desktop ~/.local/share/applications/
```

- Below one is to open text and image files in Kitty via FIle manager (Optional)

```
cp ~/.local/kitty.app/share/applications/kitty-open.desktop ~/.local/share/applications/
```

- Adding icon

```
sed -i "s|Icon=kitty|Icon=/home/$USER/.local/kitty.app/share/icons/hicolor/256x256/apps/kitty.png|g" ~/.local/share/applications/kitty*.desktop
```

```
sed -i "s|Exec=kitty|Exec=/home/$USER/.local/kitty.app/bin/kitty|g" ~/.local/share/applications/kitty*.desktop
```

Installation of Kitty with some setup done!

## Configuration of Kitty

`kitty.conf` file is used to config kitty.

Also install the fonts provided in the ttf folder for a better look and coding experience

For more regarding key bindings and configuration check https://sw.kovidgoyal.net/kitty/overview/

Theme used - https://github.com/catppuccin/kitty

Setting up option to show `Open in Kitty` in file manager on right click (context menu) can be done via https://github.com/Stunkymonkey/nautilus-open-any-terminal
